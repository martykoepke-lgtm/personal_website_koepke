# Marty Koepke Portfolio Website

Personal portfolio website showcasing work, capabilities, and contact information.

## 🚀 Quick Deploy to Vercel

### Option 1: Vercel CLI (Recommended)
1. Install Vercel CLI: `npm install -g vercel`
2. Navigate to this directory
3. Run `vercel` and follow prompts
4. To deploy to production with your custom domain: `vercel --prod`

### Option 2: Vercel Dashboard
1. Go to [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Import this repository or drag-and-drop this folder
4. Vercel will auto-detect it's a static site
5. Click "Deploy"

## 🌐 Custom Domain Setup (martykoepke.com)

### In Vercel Dashboard:
1. Go to your project settings
2. Navigate to "Domains"
3. Add `martykoepke.com` and `www.martykoepke.com`
4. Follow Vercel's DNS configuration instructions

### Update Your Domain Registrar:
Add these records to your DNS settings:

**For apex domain (martykoepke.com):**
- Type: `A`
- Name: `@`
- Value: `76.76.21.21`

**For www subdomain:**
- Type: `CNAME`
- Name: `www`
- Value: `cname.vercel-dns.com`

**Note:** DNS propagation can take up to 48 hours, but usually completes in minutes.

## 📁 Project Structure

```
martykoepke-site/
├── index.html           # Main website file
├── marty-avatar.png     # Profile photo
└── README.md           # This file
```

## 🔧 Customization

### Adding Screenshots
To add screenshots for your projects:
1. Add image files to this directory (e.g., `sophia-screenshot.png`, `vytalpath-screenshot.png`)
2. Update `index.html` image references

### Updating Content
All content is in `index.html`. Key sections:
- **Hero**: Line ~880
- **About**: Line ~920
- **Work Portfolio**: Line ~945
- **Contact**: Line ~1050

### Styling
All CSS is embedded in `<style>` tags in the `<head>` section for easy deployment.

## 📧 Contact Email
Current contact email: `marty.koepke@practicalinformatics.com`

## 🛠 Built With
- Pure HTML/CSS/JavaScript (no build process needed)
- Custom SVG icons
- Responsive design
- Smooth scroll animations

## 📝 License
© 2025 Marty Koepke. All rights reserved.
