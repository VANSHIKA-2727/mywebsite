# My Website

This repository contains a single-page portfolio website.

## Deployment

This site is ready to deploy on Vercel as a static website.

### Option 1: Deploy via Vercel Web UI
1. Push this repository to GitHub.
2. Go to https://vercel.com/new
3. Import your GitHub repository.
4. Use the default settings. Vercel will detect the static site and serve `index.html`.

### Option 2: Deploy with Vercel CLI
1. Install the Vercel CLI if needed:
   ```bash
   npm install -g vercel
   ```
2. From this folder run:
   ```bash
   cd /Users/vanshikadhawan/Desktop/mywebsite
   vercel
   ```
3. Follow the prompts to deploy.

## Local preview

To preview locally, run:

```bash
cd /Users/vanshikadhawan/Desktop/mywebsite
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
