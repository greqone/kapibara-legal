# Kapibara Legal

A minimal static site containing legal documentation for the Kapibara TikTok video automation app.

## Pages

- **[index.html](index.html)** - Homepage with app description and navigation
- **[privacy.html](privacy.html)** - Privacy Policy
- **[tos.html](tos.html)** - Terms of Service

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/create-minimal-static-site`)
4. Select the root folder (`/`) as the source
5. Click **Save**

Your site will be published at: `https://greqone.github.io/kapibara-legal/`

## Local Testing

To test the site locally, you can use any simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (npx)
npx http-server
```

Then open `http://localhost:8000` in your browser.