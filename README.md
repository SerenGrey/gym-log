# Gym Log

A simple workout tracker that runs in your phone's browser and can be added to your home screen like an app. No account, no sign-in: your data stays on your phone.

## What it does

- **Log**: date and time, type of training (Strength, Cardio, Swimming, Core, Flexibility, Class/other), exercise or machine from a drop-down, sets with weight (kg) and reps, duration/distance/calories/level for cardio, or lengths, pool length, stroke and time for swimming (distance is worked out for you), how it felt, and notes
- **Copy a previous workout**: copies every exercise from an earlier day onto the day you have selected, ready to adjust
- **"Last time" prompt**: pick an exercise and it shows what you did last time, with a button to copy those sets in
- **Personal bests**: flagged automatically when you beat your heaviest weight (or longest distance for cardio)
- **History**: every session grouped by day, filterable by exercise, with edit and delete
- **Progress**: gym days this week/month, week streak, sessions-per-week chart, progress chart per exercise (heaviest weight, estimated 1-rep max, volume, reps, distance, pace, swim pace per 100 m…), training mix and a PB list
- **Body**: weight plus optional waist, hips, chest, arm, thigh and body fat %, with a chart
- **Settings**: add or remove exercises/machines, back up and restore, export to CSV for Excel
- Works offline once it has loaded once

## Putting it on GitHub Pages

1. Sign in to [github.com](https://github.com) and click **New repository**. Name it something like `gym-log`, set it to **Public**, and click **Create repository**.
2. On the new repository page, click **uploading an existing file**. Drag in all the files from this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`) and click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two the page shows your link, e.g. `https://yourusername.github.io/gym-log/`.

A public repository means the app's code is visible to anyone, but your workout data is never uploaded: it only lives on your phone.

## Adding it to your home screen

- **iPhone (Safari)**: open the link, tap the Share button, then **Add to Home Screen**.
- **Android (Chrome)**: open the link, tap the ⋮ menu, then **Add to Home screen** / **Install app**.

Always open it from the home-screen icon so you're using the same saved data each time.

## Keeping your data safe

Data is stored in the browser on that one device. It isn't synced between phones, and clearing your browser data will remove it. Use **Settings → Back up** every week or two (the app reminds you) and save the file somewhere like Google Drive. **Restore from backup** merges a backup back in without creating duplicates.

## Updating the app later

Upload the changed file to the repository again (same name). The app picks up the new version next time you open it with a signal.
