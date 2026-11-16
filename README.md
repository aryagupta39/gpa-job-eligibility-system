# GradPath — GPA Calculator and Job Eligibility System

A responsive college mini-project built with HTML, CSS and vanilla JavaScript.

## Features
- Enter subject names, credits and grade points.
- Calculate SGPA using Σ(credits × grade points) / Σ(credits).
- Save semester results and calculate a credit-weighted CGPA.
- Check CGPA eligibility against sample job criteria.
- Demo admin form to add job opportunities.
- Browser localStorage keeps demo changes in the same browser.

## Run locally
Extract the ZIP and open `index.html` in a browser. No installation is needed.

## Deploy free with GitHub Pages
1. Create a **public** GitHub repository named `gpa-job-eligibility-system`.
2. Extract this ZIP.
3. Upload the *contents* of this folder to the repository root: `index.html`, `css/`, `js/`, `README.md`, `.nojekyll`.
4. Commit to the `main` branch.
5. Open repository **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose branch `main`, folder `/(root)`, then click **Save**.
8. After publishing, the site URL will be `https://YOUR-USERNAME.github.io/gpa-job-eligibility-system/`.

## Important limitations
This is a static demo suitable for a college presentation and GitHub Pages. Data is stored only in the current browser; it is not shared between users/devices. The admin section has no secure authentication. A production multi-user application needs a backend API, database and secure login. Do not enter real passwords or sensitive student information.

## GitHub description
GradPath is a student academic portal that calculates SGPA/CGPA and checks job eligibility based on minimum CGPA requirements.
