# Money & Bills (PWA)

Track your spending and keep track of bills. Any bill due within 2 days (adjustable in Settings) shows up on the Home screen with a "Mark as paid" button. Paying a bill records it as an expense and moves the due date to the next cycle.

## Publish on GitHub Pages

1. Create a new **Public** repository, for example `money`.
2. Upload every file in this folder (index.html, sw.js, manifest.webmanifest, and the 3 PNG icons).
3. Go to **Settings → Pages**, choose branch `main` and folder `/ (root)`, then **Save**.
4. After 1–2 minutes the app is live at `https://USERNAME.github.io/money/`

## Install on iPhone

Open the link in **Safari**, tap **Share**, then **Add to Home Screen**.

## Updating

After editing `index.html`, bump `VERSION` in `sw.js` (money-v1 → money-v2) and upload both files.

## Notes

- Data is stored only on the phone. Use Settings → Back up data regularly, and Restore from backup on a new phone.
- Removing the app from the Home Screen deletes its data.
- Your financial data never goes to GitHub; only the app files do.
