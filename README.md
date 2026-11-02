# PowerDiag OBI v2.4

Static HTML battery diagnostics dashboard.

## Run locally
Open `index.html` in Chrome or Edge.

## Deploy with GitHub Pages
1. Create a GitHub repository (for example `powerdiag-obi`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for the Pages deployment to finish. The site URL will be shown in Settings → Pages.

## Important
- Simulation mode uses generated demo values.
- Web Serial requires a supported browser (typically Chrome/Edge) and a secure context (HTTPS or localhost).
- This page currently displays raw UART input; it does not yet decode a specific BMS protocol.
- Maintenance buttons are safe demo actions and do not send real BMS commands.
