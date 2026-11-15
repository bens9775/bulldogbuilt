# Bulldog Built Calculator

A standalone, responsive Bulldog Built score calculator for GitHub Pages. The app is contained in `index.html`; it uses plain HTML, CSS, and JavaScript with no build step, dependencies, server, or database.

## Publish with GitHub Pages

1. Download `index.html` and add it to the **root** of your GitHub repository (the same level as the repository's README, if present).
2. Commit the file to your default branch (usually `main`).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your default branch and the `/(root)` folder, then click **Save**.
6. After GitHub finishes deploying, the Pages URL will appear on that settings page.

## Notes

- The calculator has 14 tests and a maximum score of 42: Bronze = 1, Silver = 2, Gold = 3.
- Blank tests are unattempted and do not add points. A entered result below Bronze earns zero points.
- Numeric results are scored automatically. The tier buttons allow manual entry when a participant knows their tier but not their precise measurement.
- The journal's paired values are interpreted in male/female order. Bodyweight-based standards use pounds.
- The journal does not fully specify the overhead-squat/FMS scoring protocol; the app reflects the listed Deep Squat / 2 FMS / 3 FMS tiers and leaves protocol interpretation to the tester.
- Save on this device uses browser local storage. Data stays in that browser and is not synced to other devices.
- Standards are based on the 2021–22 Bulldog Built Participant Journal. Confirm protocols and standards with the program administrator before using the calculator for official certification.
