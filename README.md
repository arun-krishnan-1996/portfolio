# Arun Krishnan — Portfolio

Personal portfolio website for **Arun Krishnan**, Cloud Data Engineer.

## Deploy to GitHub Pages

### 1. Create a GitHub repository

Go to [github.com/new](https://github.com/new) and create a **public** repository named:

```
your-username.github.io
```

*(Replace `your-username` with your actual GitHub username. This gives you the URL `https://your-username.github.io`.)*

Or use any name, e.g. `portfolio` — it will be at `https://your-username.github.io/portfolio`.

### 2. Push this folder

```bash
cd /Users/arun/Desktop/Port
git init
git add index.html profile.jpg README.md
git commit -m "initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under *Branch*, select **main** and **/ (root)**
4. Click **Save**

Your site will be live at `https://YOUR_USERNAME.github.io` (or `/YOUR_REPO`) within a minute.

## Files

| File | Purpose |
|---|---|
| `index.html` | Full portfolio — single-file, no build step needed |
| `profile.jpg` | Profile photo |
| `README.md` | This file |

## Customization

- **GitHub link** — search for `https://github.com` in `index.html` and replace with your actual profile URL.
- **Colors** — edit the CSS variables in `:root` near the top of `index.html`.
- **Content** — all text is inline in `index.html`, easy to find and edit.
