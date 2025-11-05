# Simple Static Site (HTML + CSS)

A tiny starter with **two nav links** you can reuse for anything. No frameworks, just HTML/CSS.

## Files
- `index.html` — home page
- `about.html` — second page
- `contact.html` — third page
- `styles.css` — shared styles

## Quick Start (Open Locally)
Just open `index.html` in your browser. That's it.

---

## Push this project to GitHub (Mac steps)

1. **Install Git (usually preinstalled on macOS)**  
   Check: `git --version`

2. **Set your Git identity (first time only):**
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "you@example.com"
   ```

3. **Create a folder and move into it (or use this one):**
   ```bash
   cd path/to/where/you/want
   ```

4. **Copy these files into your folder** (or download the zip from ChatGPT and unzip).

5. **Initialize Git and make your first commit:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: simple static site"
   ```

6. **Create a new repository on GitHub** (web):  
   - Go to GitHub → New repository → name it, keep it **Public** (or Private).  
   - **Do NOT** add a README/License/.gitignore (keeps push simple).

7. **Connect your local folder to GitHub (HTTPS easiest):**
   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git branch -M main
   git push -u origin main
   ```

> If you see an auth popup, log in with your GitHub account. For improved security, you can create a **Personal Access Token** and use it as your password.

---

## Optional: Enable GitHub Pages (free hosting)
1. Open your repo on GitHub → **Settings** → **Pages**.  
2. Source: **Deploy from a branch** → select **main** → **/(root)** → **Save**.  
3. Your site will be live at the URL shown on that page (give it a minute).

---

## Edit for your own use
- Change the `<title>` in each HTML file.
- Update text in sections.
- Adjust colors in `styles.css`.
- Add or remove links from the `<nav>` as needed.

Enjoy!
