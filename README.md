# SkillBridge — Student Career Platform

SkillBridge is a responsive frontend prototype that helps students explore sample job and internship opportunities, save roles, track applications, and monitor learning progress.

## Features
- Responsive layout for mobile, tablet, and desktop
- Search and filter demo opportunities by keywords, type, and work mode
- Save/unsave opportunities
- Application tracker with editable statuses
- Learning-path progress buttons
- Editable profile, career goal, and skills
- Browser-local demo persistence using `localStorage`
- No frameworks or build tools required

## Tech stack
- HTML
- CSS
- Vanilla JavaScript

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a browser.
3. For a local development server, open the folder in VS Code and use a static server extension, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a GitHub repository named `skillbridge`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under the build/deployment section, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. After GitHub Pages finishes publishing, your site will be available at `https://YOUR-USERNAME.github.io/skillbridge/`.

## Important demo notes
- All opportunity listings and companies in this project are fictional sample data. They are not real vacancies.
- This is a frontend-only prototype. It does not have a backend, real accounts, or real job applications.
- Profile, saved roles, application statuses, and course progress are stored in this browser's local storage. They do not sync across devices.
- Do not enter sensitive personal information.

## Customize
- Edit the `opportunities` array near the top of `script.js` to add or change demo listings.
- Update text and sections in `index.html`.
- Adjust colors and responsive styling in `style.css`.
