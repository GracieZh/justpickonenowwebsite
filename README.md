# Just Pick One - Website

This folder contains the static website for Just Pick One, designed to be deployed on GitHub Pages.

## File Structure

```
docs/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript for interactivity
├── favicon.ico         # Website favicon (placeholder)
└── screenshots/        # App screenshots and demo video
    ├── 1.png          # Home screen screenshot
    ├── 2.png          # Options management screenshot
    ├── 3.png          # Decision result screenshot
    ├── 4.png          # Settings screenshot
    ├── 5.png          # Category view screenshot
    └── vid1.mp4       # Demo video
```

## Setup Instructions

### 1. Replace Placeholder Files

Before deploying, replace the following placeholder files with actual content:

- `favicon.ico` - Create a proper favicon for your app
- `screenshots/1.png` through `screenshots/5.png` - Add actual app screenshots
- `screenshots/vid1.mp4` - Add a demo video showcasing your app

### 2. Customize Content

Update the following sections in `index.html`:
- App store and Google Play download links
- Email addresses for support, bugs, and feature requests
- Social media links in the footer
- Any other contact information

### 3. Deploy to GitHub Pages

1. **Push to GitHub**: Ensure this `docs/` folder is committed and pushed to your GitHub repository.

2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Under "Branch", select "main" (or your default branch)
   - Under "Folder", select "/docs"
   - Click "Save"

3. **Access Your Site**: Your website will be available at `https://[username].github.io/[repository-name]`

### 4. Custom Domain (Optional)

If you want to use a custom domain:
1. Go to repository Settings → Pages
2. Under "Custom domain", enter your domain name
3. Configure DNS records as instructed
4. Add the domain to your repository's `CNAME` file if needed

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Glass morphism effects, smooth animations, and gradient backgrounds
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Optimized CSS and minimal JavaScript
- **Accessibility**: Proper contrast ratios and semantic markup

## Customization

### Colors
The main color scheme uses a purple gradient. To change colors:
- Update the CSS custom properties in `styles.css`
- Modify gradient definitions in hero and download sections

### Content
- Edit text content directly in the HTML files
- Update feature descriptions, contact information, and links
- Add or remove sections as needed

### Analytics
To add analytics, include your tracking code in `script.js` or add it directly to the HTML files.

## Support

For questions about this website or deployment issues, check the GitHub repository issues or contact the development team.