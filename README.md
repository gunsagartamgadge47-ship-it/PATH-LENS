[README.md](https://github.com/user-attachments/files/31207881/README.md)
# PATH-LENS Dashboard

A standalone, client-side research dashboard for de-identified PATH-LENS case records and provisional FIR intake.

## Contents

- `PATH-LENS_Dashboard_1.html` — the complete dashboard. Open it locally in a modern browser or publish it as a static site.
- `README.md` — this guide.

## GitHub upload

1. Create a new GitHub repository.
2. Upload `PATH-LENS_Dashboard_1.html` and this `README.md` to the repository root.
3. Optional: rename `PATH-LENS_Dashboard_1.html` to `index.html` if you want the dashboard to open at the repository's GitHub Pages root URL.
4. In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will provide the public Pages URL after deployment.

## Important research safeguards

- The dashboard is a descriptive research prototype, not a diagnostic, predictive, legal, sentencing, bail, or detention tool.
- FIR-derived records are de-identified and marked unverified until researcher review.
- The provisional FIR report records allegations, evidence gaps, and candidate references only; it does not create an automated risk formulation.
- Use only with authorised material and follow applicable privacy, security, ethics, and data-retention requirements.

## Technical notes

- No server or build step is required.
- The PDF reader uses a public PDF.js CDN at the time a text-based PDF is processed. Pasted text and `.txt` intake work without that dependency.
- The dashboard stores active data in the browser session only; exports are user-initiated downloads.
