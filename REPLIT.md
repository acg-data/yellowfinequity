# How to Deploy Yellowfin Equity to Replit

## Quick Start (3 Steps)

### 1. Create New Replit
1. Go to [replit.com](https://replit.com)
2. Click "Create Repl"
3. Select "HTML, CSS, JS" template
4. Name it `yellowfin-equity`

### 2. Clone the Repository
In the Replit Shell, run:

```bash
git clone https://github.com/acg-data/yellowfinequity.git temp
mv temp/* .
mv temp/.* . 2>/dev/null || true
rm -rf temp
```

### 3. Start the Server
The `.replit` file is already configured - just click **Run**!

Your site will be available at the Replit URL provided in the preview window.

---

## What's Included

This repository is a complete static HTML/JS/CSS website with:

- **24 Pages**: index, about, criteria, contact + 20 industry pages
- **Shared Assets**: `css/styles.css` and `js/main.js`
- **No Build Step Needed**: Pure HTML/CSS/JS with CDN resources

---

## Local Development

If you want to run locally:

```bash
# Using Python (recommended)
python server.py

# Or using Python module
python -m http.server 8000

# Using Node.js
npx serve
```

Then open `http://localhost:5000` (or `http://localhost:8000`)

---

## Customizing for Replit

### Change the Run Command
Edit `.replit` to customize:

```toml
[workflows.workflow.tasks]
task = "shell.exec"
args = "python -m http.server 8000"
waitForPort = 8000
```

### Custom Domain
In Replit: 
1. Go to "Deployment" 
2. Link your custom domain
3. Deploy as a Static Site

---

## File Structure

```
yellowfin-equity/
├── index.html              # Homepage
├── about.html             # About page
├── criteria.html          # Industries overview
├── contact.html           # Contact form
├── industries/            # 20 industry pages
│   ├── b2b-services.html
│   ├── cpg.html
│   ├── dental.html
│   └── ... (17 more)
├── css/
│   └── styles.css         # Shared styles
├── js/
│   └── main.js            # Shared JavaScript
├── assets/
│   └── images/            # Empty, ready for assets
├── server.py              # Python HTTP server
├── .replit                # Replit configuration
└── README.md              # This file
```

---

## Troubleshooting

### Site Not Loading?
- Make sure you ran the git clone command first
- Click "Stop" then "Run" again
- Check the Shell for errors

### Port Already in Use?
The server runs on port 5000 by default. If that port is taken, you can modify `server.py` to use a different port.

### Missing Assets?
- The `assets/images/` folder is empty by design
- Add your own images if needed

### CDN Issues?
- Replit requires internet access for CDNs (Google Fonts, Font Awesome, Tailwind)
- Check that Replit has network access enabled

---

## Support

For issues, visit:
- GitHub: https://github.com/acg-data/yellowfinequity
- Replit Docs: https://docs.replit.com

---

**Deployed with ❤️ using Replit**