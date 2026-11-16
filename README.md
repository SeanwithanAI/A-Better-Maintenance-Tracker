<div align="center">

# A Better Maintenance Tracker

**Car Service & Cost Planner: what's due, what it costs, and how long your car will last**

![Version](https://img.shields.io/badge/version-2026--11--16%20mk2-C2410C)
![Single file](https://img.shields.io/badge/single%20file-HTML-9A3412)
![No account needed](https://img.shields.io/badge/no%20sign--up-required-334155)
![PageVault ready](https://img.shields.io/badge/PageVault-ready-2563eb)

**[▶ Open it online](https://seanwithanai.github.io/A-Better-Maintenance-Tracker/)** · nothing to install · your data stays on your device

*by SeanwithanAI*

</div>

![Agenda: upcoming maintenance with due dates, priority, DIY and shop cost estimates, and the car's outlook](docs/screenshots/agenda.png)

---

## Overview

A Better Maintenance Tracker builds a maintenance schedule for each of your cars and tells you what's coming up. It shows what each job costs if you do it yourself versus at a shop, keeps a full service history, and estimates how many miles and years the car has left. It's all in one HTML file, with nothing to install and no sign-up.

## Features

- **Add a car in seconds.** Enter the VIN and the year, make, model, engine, transmission and drive type are decoded from the **NHTSA** database. Or fill them in by hand.
- **A schedule made for that car.** Intervals start from typical values for the powertrain (gas, diesel, hybrid or EV), transmission, drive type and driving conditions.
- **Details for every item.** Tap an item's name (or **Details**) to see what it is, why it matters, how it's done step by step, and what you'll need, with its interval, last service, next due date and cost. Add your own how-to notes (part numbers, sizes, tips) to any item. **Watch how** searches videos for your exact car.
- **Your factory schedule.** The owner's manual is the most accurate source, so the Schedule page tracks how much of your schedule has been checked against it (a progress bar and a *✓ Manual* or *Typical* tag on every item). Three ways to get there: **Check items one by one** (a guided walk through each item, with normal and severe intervals, or *Not in my manual* to turn it off); **Paste from manual** (paste the schedule text as written – one item per line or under headings like “Every 30,000 miles:”, with an optional *Severe* section – and see a preview before it updates your items); or **Find my manual**, a search for your exact year, make and model.
- **Agenda.** Everything due in the next 30 days, 3 months, 6 months or year, ranked Critical, Medium or Low. Shows the **DIY vs. shop** cost and estimated time for each job.
- **History and calendar.** Every service you've logged, plus a calendar of what's coming that you can export to your own calendar app.
- **Expenses.** Spending by category and by year, DIY savings, cost per mile, and a full service log you can filter by DIY or shop.
- **Built-in job timer** for timing DIY work, so time estimates learn from your own jobs.
- **Lifespan.** Expected lifetime mileage and the year the car is *likely useful until*, based on reliability, driving conditions, your habits, your regular routes and how well it's maintained. Shows which maintenance would add the most life.
- **Safety recalls.** Checks NHTSA for open recalls on your car.
- **Odometer tracking.** Update the odometer now and then, and yearly mileage is re-estimated so due dates stay accurate.
- **Multiple cars,** each with its own schedule and history.
- **Works on phones,** with a bottom tab bar and full-width dialogs on small screens.
- **Backup and restore,** with undo if you restore the wrong file.
- **Download app + data.** In **Back up & restore**, one click downloads a .zip with this version of the app, a backup of your data, and a short note on how to restore it. Open the HTML anywhere and restore the backup to pick up where you left off. In PageVault it's the exact file that's installed.

## Screenshots

| Expenses | Lifespan |
|---|---|
| ![Expenses: totals, DIY savings, by category, by year and the service log](docs/screenshots/expenses.png) | ![Lifespan: expected lifetime mileage, likely useful until 2041, and how it's calculated](docs/screenshots/life.png) |

<sub>Screenshots use made-up example data.</sub>

## Getting started

1. Open `A-Better-Maintenance-Tracker-<date>-<mk>.html` in any modern browser, or open it from **PageVault**.
2. Click **+** to add a car. Decode the VIN or fill in the details, then enter the current odometer reading and your yearly miles.
3. Choose how the history should start: *on schedule*, *brand new* or *unknown*.
4. Check the **Agenda**, and use **Log maintenance** whenever you do a job.

Online lookups (VIN decoding, recalls, route maps) use free public services. Everything else works offline.

## Opening the file on your devices

**Easiest: the web link.** Open **[seanwithanai.github.io/A-Better-Maintenance-Tracker](https://seanwithanai.github.io/A-Better-Maintenance-Tracker/)** on any phone, tablet or computer. It's this same app, served by GitHub, and it always has the newest version. Nothing is sent anywhere: your data is saved in that browser on that device, just like the downloaded file. On iPhone or iPad, open it in Safari, tap **Share** (on iOS 26 and later, tap **•••** first), then **Add to Home Screen** to keep it like an app. On Android, use Chrome's **⋮ → Add to Home screen**.

Prefer to keep your own copy of the file? The steps below cover that.

The app is one self-contained `.html` file: no install, no account, nothing else to download. Download `A-Better-Maintenance-Tracker-<date>.html`: open it in the file list above, then use the **Download raw file** button (↓) at the top right of the file view.

**Desktop (Windows, macOS, Linux)**
1. Download the file and move it somewhere permanent, like Documents.
2. Double-click it. It opens in your default browser (Chrome, Edge, Firefox, Safari and Brave all work).
3. Bookmark it, and always open it the same way: same file, same place, same browser. Your data is saved in that browser for that file, so a copy in another folder or another browser starts empty.

**iPhone and iPad**
**Because of iOS, an HTML file saved on your iPhone or iPad can't be opened in Safari.** iOS doesn't offer Safari as a way to open it, and tapping the file in the Files app only shows a preview with the buttons turned off. Use one of these instead:
- **The web link (recommended).** See above.
- **PageVault.** Open the app's PageVault link in **Safari**, then tap **Share** (on iOS 26, tap **•••** first, then **Share**). Scroll down the list and tap **Add to Home Screen**. If it isn't there, tap **Edit Actions** at the bottom of the list and add it. It then opens like a regular app, and your data is saved on your server and syncs with your other devices.
- **Microsoft Edge (may work).** Save the file to the Files app, then try opening it with Edge (in Files, open the file, tap **Share** and choose **Edge**). Keep backups: data saved this way can be lost if Edge clears its storage.

**Android**
1. Download the file in Chrome.
2. Open it from Chrome: **⋮ → Downloads** and tap the file (or from the Files app, **Open with → Chrome**).
3. Open it from Chrome's Downloads each time. A home-screen shortcut to a downloaded file may stop working after Chrome restarts.
4. Turn on backups (the app reminds you every 7 days), or use **PageVault** and **⋮ → Add to Home screen** so your data lives on your server instead.

**Moving to another device:** download a backup in the app, open the same version on the new device, and restore the backup there. With PageVault there's nothing to move.

## Where your data is stored

| Opened from… | Saved to | Badge shown next to the car |
|---|---|---|
| **PageVault** | Your own server only, separately for each signed-in person. Nothing is kept in the browser. | *Saved to your server* |
| **A local file** | This browser only. Use **Back up & restore** to keep a copy. | *Saved on this device only* |

## Versioning

Only the newest release is kept in the repo: `A-Better-Maintenance-Tracker-2026-11-16-mk2.html`. Each new release replaces it, and `docs/index.html` (what the web link opens) is updated to match. Your data isn't stored in the file, so moving to a new release keeps it (if you use the downloaded file, open the new one the same way as before, in the same browser, and download a backup first to be safe).

Releases are named with their date. The first release of a day is just the date; later releases that same day add `mk1`, `mk2`, `mk3`… (the count starts over each day). The version is also shown inside the app.

### Changelog

Every release so far, newest first. Older releases are listed for reference; only the current one is available to download.

| Version | Notes |
|---|---|
| **2026-11-16 mk2** | **Use it online.** The app now has a web link, [seanwithanai.github.io/A-Better-Maintenance-Tracker](https://seanwithanai.github.io/A-Better-Maintenance-Tracker/), that works on any device, including iPhone and iPad, and always has the newest version. The preview shown when the file can't run points to it. |
| **2026-11-16 mk1** | The preview now says plainly that, because of iOS, an HTML file saved on an iPhone or iPad can't be opened in Safari, and points to PageVault instead. |
| **2026-11-16** | The preview shown when the file can't run (like in the iPhone Files app) now explains how to open it on a computer, Android, iPhone and iPad. Map messages no longer mention other apps. |
| **2026-11-15 mk3** | Same as 2026-11-15 mk2, re-released so PageVault picks up the update. |
| **2026-11-15 mk2** | **CVT transmissions count toward the lifespan estimate** (×0.90), since they tend to wear out sooner than conventional automatics. Skipped when you enter your model's own typical lifespan, which already accounts for it. |
| **2026-11-15 mk1** | **More accurate lifespan.** Typical age now depends on body type (about 17 years for cars, 20 for SUVs and vans, 25 for pickups, from a 2024 study of US vehicle scrappage), guessed from the model or VIN. New optional **Typical lifespan for this model** (e.g. from iSeeCars' used-car data) replaces the generic powertrain figure. |
| **2026-11-15** | **Phone keyboard fix.** Pop-up forms now fit above the on-screen keyboard and keep the field you're typing in visible, instead of sliding it out of view on iPhone. |
| **2026-11-14 mk2** | **Download app + data (.zip)** replaces Download this app: one click gives a zip with the app's HTML, your backup and a how-to-restore note. |
| **2026-11-14 mk1** | **Download this app** in **Back up & restore**: the HTML file for this version, to keep or run on its own. |
| **2026-11-14** | Day, Dark or Auto appearance, chosen from the **⋯** menu (Auto follows your device, as before). The map switches to its dark style with the app. |
| **2026-11-13** | Version bump only, no changes. |
| **2026-11-12 mk1** | Details for every schedule item: what it is, why it matters, brief how-to steps and what you'll need (built in for all standard items, plus hood/liftgate struts, A/C desiccant and underbody flush), with your own how-to notes per item, *Watch how* video search, and Log it / Edit shortcuts. |
| **2026-11-12** | Factory schedule: progress bar and *✓ Manual* / *Typical* tags showing how much of each car's schedule matches its owner's manual, a guided *Check items one by one* walkthrough, *Paste from manual* (reads manual text, including “Every 30,000 miles:” headings, miles/km, months/years and a severe-conditions section, with a preview), and a *Find my manual* link. CSV/JSON imports count as checked. |
| **2026-11-11 mk15** | Phone-friendly: nothing is cut off on small screens (320–412 px). The bottom tab bar fits all six tabs and stays fully on screen, *Done* buttons no longer get pushed off the edge by long *Overdue* labels, the car picker shows the nickname on phones, and times like "1 h 57 min" no longer break mid-value. |
| **2026-11-11 mk14** | New badge showing where data is saved: *Saved to your server* in PageVault (no "Backup due" reminder there), *Saved on this device only* elsewhere. |
| **2026-11-11 mk13** | Previous release |

<div align="center"><sub>A Better Maintenance Tracker · Car Service & Cost Planner · by SeanwithanAI</sub></div>
