# SoberSteps Landing Page

Landing page dla SoberSteps — deploy na GitHub Pages.

## Deploy na GitHub (nowe repo)

1. Utwórz repo: https://github.com/new
   - Owner: `soberstepsdev`
   - Name: `sobersteps-landing`
   - Public, bez README

2. Skopiuj pliki do repo (zachowaj strukturę):
   ```
   index.html
   style.css
   README.md
   .github/workflows/deploy.yml
   ```

3. Push do `main`:
   ```bash
   cd landing
   git init
   git add .
   git commit -m "Landing page"
   git remote add origin https://github.com/soberstepsdev/sobersteps-landing.git
   git push -u origin main
   ```

4. GitHub → Settings → Pages → Source: **GitHub Actions**
   (workflow deploy uruchomi się automatycznie po push)

5. URL: **https://soberstepsdev.github.io/sobersteps-landing/**

## Waitlist

Waitlist (soberstepsdev.github.io/sobersteps) przekierowuje przycisk "Join the waitlist" na ten landing.
