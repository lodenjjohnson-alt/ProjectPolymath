# Polymath Path

A structured self-development web app for building polymathic range through daily missions, domain skill trees, capstone projects, XP, ranks, weekly reviews, and proof-of-work logging.

## Features

- Eight default domains:
  - Athletic Mastery
  - Logic & Mathematics
  - Science & Engineering
  - History & Civilization
  - Business & Wealth
  - Communication & Leadership
  - Philosophy & Theology
  - Arts & Culture
- Daily mission generation
- Proof-of-work logging before mission completion
- XP and rank progression
- Domain progress compass
- Capstone project tracker
- Weekly review system
- Operation archive
- Import/export backup system
- Runs fully in the browser using localStorage

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Create a new GitHub repository named `polymath-path`.
2. Upload these files:
   - `index.html`
   - `styles.css`
   - `app.js`
   - `README.md`
3. Go to repository `Settings` → `Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save. GitHub will give you a live URL.

## Push with Git

```bash
git init
git add .
git commit -m "Initial Polymath Path app"
git branch -M main
git remote add origin https://github.com/lodenjjohnson-alt/polymath-path.git
git push -u origin main
```

## Philosophy

A polymath is not built by collecting trivia. A polymath is built through deliberate cycles:

1. Learn.
2. Produce.
3. Test.
4. Correct.
5. Integrate.
6. Repeat.

This app forces that cycle.
