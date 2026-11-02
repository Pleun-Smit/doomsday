# The Doomsday Watch

A small planner for catching up on Marvel films before **Avengers: Doomsday** (in theaters 18 December 2026).

- Add the films and series you want to watch, in the order you want to watch them
- Set a finish date and how many minutes you can watch on each day of the week
- Get a day-by-day schedule, a "today" view, and a live on-track / behind status
- Check things off as you go; the schedule re-plans itself around what's left
- Optional: split long films across days, with timestamps for where to stop and resume
- Countdown to release day
- Sync link + backup file to move your plan between devices

It's a single `index.html` file with no build step, so it runs anywhere, including GitHub Pages.

## Put it on GitHub Pages

1. Sign in at [github.com](https://github.com) (create a free account if you don't have one).
2. Click **+** (top right) → **New repository**.
   - Name it something like `doomsday-watch`.
   - Set it to **Public** (GitHub Pages is free for public repositories).
   - Click **Create repository**.
3. On the new repository page, click **uploading an existing file** (or **Add file → Upload files**).
4. Drag in `index.html` (and this `README.md` if you like), then click **Commit changes**.
5. Go to **Settings → Pages** (left sidebar).
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Branch: **main**, folder: **/ (root)** → **Save**.
6. Wait a minute or two, then refresh the Pages settings. Your site address appears at the top, like
   `https://YOUR-USERNAME.github.io/doomsday-watch/`

Open that link on your phone and use **Share → Add to Home Screen** (iPhone) or **⋮ → Add to Home screen** (Android) to use it like an app.

## Updating the app later

Open `index.html` in your repository, click the pencil icon (or upload a new version), and commit. The site updates within a minute or two. Your watchlist and progress are not affected, because they live in your browser, not in the file.

## Your data and multiple devices

Your plan is saved in the browser you use (localStorage). Nothing is sent anywhere. Each device has its own copy, so to continue on another device:

- **Settings → Copy sync link**, then open that link on the other device. It replaces that device's plan with yours.
- Or **Export backup** to a `.json` file and **Import backup** on the other device.

Clearing your browser's site data erases the plan, so export a backup now and then.

## Notes

- Runtimes in the suggested lineup are approximate. Edit any title to fix its runtime.
- Checking a title in the **Watchlist** marks it as already seen and does not use today's watch time. Pressing **Watched** in the schedule or the Today panel counts it toward today, so the rest of today's plan moves to tomorrow.
- Fan-made; not affiliated with Marvel or Disney.
