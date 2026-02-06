# Amina Emenena - Personal Website

## Preview Locally

1. Open `index.html` in your browser
2. Use the theme switcher in the top-right to preview all 4 themes:
   - **Minimal** - Clean, light, modern typography
   - **Dark** - Developer-focused terminal aesthetic
   - **Corporate** - Traditional business portfolio
   - **BuildFlow** - Matches your SAAS site styling

## Deploy to GitHub Pages

1. Create a new repo on GitHub (e.g., `amina-obe.github.io` or `personal-site`)
2. Push this code:
   ```bash
   cd amina-website
   git init
   git add .
   git commit -m "Initial website"
   git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to repo Settings > Pages > Source: Deploy from branch (main)
4. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Customize

- Edit `index.html` for content changes
- Edit CSS files in `css/` folder for styling
- To change default theme, edit line 12 in `index.html`
- Remove the theme switcher div once you've chosen a theme

## Custom Domain (amina.cloud)

1. Add a `CNAME` file containing: `www.amina.cloud`
2. In your domain registrar, add:
   - A records pointing to GitHub's IPs (185.199.108-111.153)
   - CNAME record: www -> YOUR_USERNAME.github.io
