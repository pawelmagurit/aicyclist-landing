# AI Cyclist Landing Page

This directory contains a simple static landing page for AI Cyclist that can be deployed to GitHub Pages or any static hosting service.

## Files

- `index.html` - Main landing page
- `terms.html` - Terms of Service
- `privacy.html` - Privacy Policy
- `styles.css` - Styling for all pages
- `logo.svg` - Full logo with text
- `logo-icon.svg` - Icon-only logo

## Deployment to GitHub Pages

1. **Create a new GitHub repository** (e.g., `aicyclist-landing`)

2. **Initialize and push the files:**
   ```bash
   cd landing-page
   git init
   git add .
   git commit -m "Initial landing page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/aicyclist-landing.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Navigate to Pages section
   - Select source: "Deploy from a branch"
   - Choose branch: `main`
   - Choose folder: `/ (root)`
   - Click Save

4. **Your site will be available at:**
   - `https://YOUR_USERNAME.github.io/aicyclist-landing/`

## URLs for Garmin Developer Program

Once deployed, you can use these URLs:

- **Landing Page:** `https://YOUR_USERNAME.github.io/aicyclist-landing/`
- **Logo:** `https://YOUR_USERNAME.github.io/aicyclist-landing/logo.svg`
- **Icon:** `https://YOUR_USERNAME.github.io/aicyclist-landing/logo-icon.svg`
- **Terms:** `https://YOUR_USERNAME.github.io/aicyclist-landing/terms.html`
- **Privacy:** `https://YOUR_USERNAME.github.io/aicyclist-landing/privacy.html`

## Custom Domain (Optional)

If you have a custom domain, you can:
1. Add a `CNAME` file with your domain name
2. Configure DNS records as per GitHub Pages documentation
3. Update the domain in repository settings

## Local Testing

To test locally, you can use any simple HTTP server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server -p 8000

# Then open http://localhost:8000 in your browser
```

