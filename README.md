# React CLI Website

Static documentation website for [React CLI](https://github.com/Debarghya21/React-CLI).

## Deploying to GitHub Pages

### Option 1: GitHub Actions (Recommended)

1. Create a new repository on GitHub (e.g., `react-cli-website`)
2. Push this code to the repository:
   ```bash
   cd react-cli-website
   git init
   git add .
   git commit -m "Initial commit: React CLI website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/react-cli-website.git
   git push -u origin main
   ```
3. Go to your repository **Settings → Pages**
4. Under **Source**, select **GitHub Actions**
5. The workflow will automatically deploy on every push to `main`
6. Your site will be live at: `https://<your-username>.github.io/react-cli-website/`

### Option 2: Deploy from Branch

1. Create a new repository and push the code (same as steps 1-2 above)
2. Go to your repository **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Select the **main** branch and **/ (root)** folder
5. Click **Save**
6. Your site will be live at: `https://<your-username>.github.io/react-cli-website/`

## Local Development

Simply open `index.html` in your browser:

```bash
open index.html
# or
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Files

```
react-cli-website/
├── index.html                          # Main HTML page
├── styles.css                          # All styles
├── script.js                           # Interactivity (typewriter, copy, animations)
├── .github/workflows/deploy.yml        # GitHub Actions deployment
└── README.md                           # This file
```
