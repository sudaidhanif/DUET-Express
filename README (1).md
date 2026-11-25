# DUET Express: Bus Reservation System (web version)

A Smart C++ Based Bus Booking and Seat Management System. Programming Fundamentals (C++), Artificial Intelligence.
Submitted by: Sudaid Hanif (68), Zoraiz Sultan (66), Rao Faizan (98). Submitted to: Ma'am Ayesha.

The website re-implements the rules of `main.cpp` in JavaScript. It is a separate implementation and is NOT connected to the C++ executable.

Official university: Dawood University of Engineering and Technology (DUET), DUET Transport & Point Service. Tagline: Your Route, Your Ride, Your Campus. No official logo is used; the text identity can be replaced later.

## Interface
Role-based collapsible sidebar (hamburger on mobile) and an 8-step booking journey. Website-only extensions: passenger accounts, login, profile, personal dashboard, bus-name and partial search, localStorage persistence. All other rules come from main.cpp.

## Run locally
Open `index.html` in a browser. No build step.

## Files
`index.html` (HTML, CSS and JS in one file), `docs/` (FUNCTION_MAPPING, DEMO_SCRIPT, TEST_REPORT, CHANGELOG), `screenshots/`.

## Deploy on GitHub Pages
1. Create a GitHub account and a new public repository, e.g. `duet-express`.
2. Click "Add file", "Upload files", drag `index.html`, `README.md` and the `docs` folder, then "Commit changes".
3. Repository "Settings", "Pages". Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/ (root)`, Save.
4. Wait about a minute and refresh the Pages screen. The URL appears there, normally `https://<username>.github.io/duet-express/`.
5. Open the URL and run one booking to verify.
To update: edit or re-upload `index.html` and commit.
Netlify alternative: log in at netlify.com, "Add new site", "Deploy manually", drop the folder.
Repository URL: `<add after creating>`. Website URL: `<add after verifying>`.

## Testing
See `docs/TEST_REPORT.md` (automated tests in headless Chromium plus a manual checklist) and `docs/CHANGELOG.md`. Printing was verified by print emulation only; confirm with the real print preview. Nothing has been deployed yet.

## Reset demo data
About page or Admin Trips tab, "Reset demo data", confirm.

## Limitations
Not production-ready. Browser storage can be edited by users and is not a database; passwords and role checks run in the browser, so they are demonstration-only. A real system needs a backend, a database, server-side authentication/authorization and secure password hashing. The 3-attempt admin limit resets on page reload. Data is stored in the browser's localStorage (per browser, not shared across devices). Passenger and admin login run in the browser and are classroom demonstrations, not production security. The admin password is stored only as an obfuscated hash, which is not real protection.
