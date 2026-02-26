# PIPS Pro™ Marketing Website

Professional marketing webpage for PIPS Pro - Property Inspection Profit System

## Features

- **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Modern UI** - Clean, professional design with PIPS Pro branding (navy blue #0B1C3F, gold #FFD700)
- **Complete Sections**:
  - Hero section with compelling CTA
  - Features showcase (6 key features)
  - Benefits grid (6 value propositions)
  - Pricing table (4 tiers: Freemium, Basic, Pro, Business)
  - FAQ accordion (6 common questions)
  - Footer with links and legal info

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Navigate to project directory:
```bash
cd /home/ubuntu/pips-pro-website
```

3. Deploy:
```bash
vercel
```

4. Follow the prompts to link your project

### Option 2: Deploy via Vercel Dashboard

1. Create a new repository on GitHub
2. Push this folder to the repository:
```bash
git init
git add .
git commit -m "Initial commit: PIPS Pro marketing website"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

3. Go to [vercel.com](https://vercel.com)
4. Click "New Project"
5. Import your GitHub repository
6. Vercel will auto-detect the static site and deploy

### Option 3: Deploy via Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New..." → "Project"
3. Drag and drop the `/home/ubuntu/pips-pro-website` folder
4. Vercel will automatically deploy

## Files Included

- `index.html` - Main webpage with all sections
- `vercel.json` - Vercel configuration
- `README.md` - This file

## Customization

To customize the website:

1. **Update App URL**: Replace `https://pipsproapp-axbn2mii.manus.space` with your production app URL
2. **Add Analytics**: Insert Google Analytics or other tracking code before `</head>`
3. **Update Legal Links**: Add actual Privacy Policy, Terms of Service, Cookie Policy pages
4. **Add Contact Form**: Integrate email capture or contact form in CTA section

## Tech Stack

- Pure HTML5, CSS3, JavaScript
- No dependencies or build process required
- Optimized for fast loading and SEO
- Mobile-first responsive design

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2026 PIPS Pro™. All rights reserved.
