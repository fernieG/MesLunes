# Mes Lunes

A simple, private menstrual cycle tracker that runs entirely in your browser. One HTML file, no accounts, no server, no tracking.

## What it does

- Predicts your next period, with a likely date range
- Estimates ovulation and the fertile window
- Calendar view of periods, predictions, fertile days and ovulation
- Keeps a history of past cycles and the symptoms you logged
- Adjustable luteal phase length (default 14 days)
- Download your data as a backup file and restore it from that file

## How the estimates work

- Cycle length is the average of your last 6 cycles. With fewer than 3 logged cycles it assumes a 26 to 30 day range.
- Ovulation = expected next period minus the luteal phase (14 days by default).
- Fertile window = 5 days before ovulation through 1 day after.

This is the standard calendar method. It cannot confirm ovulation, varies between people and cycles, and is **not a method of contraception**. It is not medical advice.

## Privacy

Everything you enter is stored in your browser's `localStorage` on your own device. Nothing is sent anywhere. Use **History > Download backup** to save a `.json` file in your own storage (Files, iCloud Drive, Google Drive), and **Restore from file** to load it back, because clearing site data erases it. Never commit personal data to this repository.

## Run it

Open `index.html` in a browser, or host the folder with GitHub Pages (Settings > Pages > Deploy from a branch > `main` / root). On a phone, open the hosted page and use "Add to Home Screen".

## License

MIT, see `LICENSE`.
