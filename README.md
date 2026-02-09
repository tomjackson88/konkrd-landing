# Konkrd Hero Section

Landing page hero section for Konkrd - AI-powered health insurance assistant.

## Quick Deploy to Vercel

### Option 1: Vercel CLI (Recommended)

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Navigate to this folder and deploy:
```bash
cd konkrd-staging
vercel
```

3. Follow the prompts. You'll get a live URL like `konkrd-hero.vercel.app`

### Option 2: Vercel Dashboard

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repo
5. Click Deploy

### Option 3: Netlify Drop (Fastest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the `public` folder onto the page
3. Instantly get a live URL

## Local Development

```bash
npm start
```

This will serve the site locally at `http://localhost:3000`

## Project Structure

```
konkrd-staging/
├── public/
│   └── index.html    # Main HTML file with all styles
├── package.json
├── vercel.json       # Vercel deployment config
└── README.md
```

## Assets

All image assets are hosted on Figma's CDN and will expire after 7 days. For production, download and host these assets on your own CDN:

- Logo: `konkrd-colour-logo.png`
- Tagline: `life-admin-conquered.png`
- 3D Icons: `icon-3d-headset.png`, `icon-3d-chat.png`
- Sparkle: `sparkle.png`
- Konkrd Icon: `konkrd-icon.png`
- Down Arrow: `down-arrow.png`
