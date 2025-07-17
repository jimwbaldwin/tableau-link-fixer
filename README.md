# Tableau Link Fixer

A simple web tool that cleans up broken Tableau bookmark links by removing unnecessary parameters and IDs. Try it out at [https://jimwbaldwin.github.io/tableau-link-fixer/](https://jimwbaldwin.github.io/tableau-link-fixer/).

## What it does

Tableau bookmark links often contain extra parameters and IDs that can cause issues when shared or bookmarked. This tool automatically detects and removes these problematic parts, leaving you with a clean, working link.

### Example

**Broken link:**
```
https://us-west-2b.online.tableau.com/#/site/yoursite/views/YourDashboard/YourView/a1b2c3d4-e5f6-7890-abcd-ef1234567890/YourReport?:iid=1
```

**Fixed link:**
```
https://us-west-2b.online.tableau.com/#/site/yoursite/views/YourDashboard/YourView
```

## Features

- 🎯 Simple, clean interface
- 🔗 Automatic link detection when pasting
- 📱 Mobile-friendly design
- 🚀 No external dependencies
- ⚡ Works entirely in the browser

## How to use

1. Copy your broken Tableau bookmark link
2. Paste it in the textbox
3. Click "Fix Link" (or it will auto-detect when you paste)
4. Use the fixed link

## Deployment

This is a static website that can be easily deployed to GitHub Pages:

1. Push this repository to GitHub
2. Go to your repository settings
3. Scroll down to "GitHub Pages" section
4. Select "Deploy from a branch"
5. Choose the `main` branch and `/ (root)` folder
6. Click "Save"

Your site will be available at `https://yourusername.github.io/tableau-link-fixer/`

## Local Development

To run locally, simply open `index.html` in your web browser. No server required!

## License

MIT License - feel free to use and modify as needed.
