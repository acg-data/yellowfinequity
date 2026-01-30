# Yellowfin Equity Website - Complete 24-Page Structure

## 📁 Folder Structure
```
yellowfin-equity/
├── index.html              # Homepage with hero, partners carousel, stats
├── criteria.html           # Industries overview grid
├── about.html              # Company story, values, location
├── contact.html            # Contact form with map
├── industries/             # 20 individual industry criteria pages
│   ├── b2b-services.html
│   ├── cpg.html
│   ├── dental.html
│   ├── electrical.html
│   ├── environmental.html
│   ├── healthcare.html
│   ├── home-services.html
│   ├── hvac-plumbing.html
│   ├── infrastructure.html
│   ├── insurance.html
│   ├── landscaping.html
│   ├── logistics.html
│   ├── manufacturing.html
│   ├── msp-data.html
│   ├── paving.html
│   ├── pest-control.html
│   ├── restoration.html
│   ├── roofing.html
│   ├── software.html
│   └── veterinarian.html
├── css/
│   └── styles.css          # Shared styles with brand colors
├── js/
│   └── main.js             # Shared JavaScript for interactions
├── assets/
│   └── images/             # Empty, ready for assets
├── server.py               # Python HTTP server for local dev
├── .replit                 # Replit configuration
├── REPLIT.md               # Replit deployment guide
└── README.md               # This file
```

## ✅ All 24 Pages Complete

### Core Pages (4)
1. **index.html** - Landing page with hero, partner carousel, stats, process, deals
2. **criteria.html** - Grid overview of all 20+ industries
3. **about.html** - Company mission, values, Austin location
4. **contact.html** - Full contact form with industry/revenue selectors

### Industry Pages (20)
5. **b2b-services.html** - B2B Services investment criteria
6. **cpg.html** - Consumer Packaged Goods criteria
7. **dental.html** - Dental practices criteria
8. **electrical.html** - Electrical services criteria
9. **environmental.html** - Environmental services criteria
10. **healthcare.html** - Healthcare services criteria
11. **home-services.html** - Home services criteria
12. **hvac-plumbing.html** - HVAC/Plumbing criteria
13. **infrastructure.html** - Infrastructure engineering criteria
14. **insurance.html** - Insurance brokerages criteria
15. **landscaping.html** - Commercial landscaping criteria
16. **logistics.html** - Logistics and distribution criteria
17. **manufacturing.html** - Manufacturing criteria
18. **msp-data.html** - MSP/Data services criteria
19. **paving.html** - Paving services criteria
20. **pest-control.html** - Pest control criteria
21. **restoration.html** - Restoration services criteria
22. **roofing.html** - Roofing services criteria
23. **software.html** - Software/SaaS criteria
24. **veterinarian.html** - Veterinarian services criteria

## 🎨 Features Implemented (All Pages)

### Visual Design
- ✅ Yellowfin brand colors (EDF0EF, 002355, FEFEFE, F9D300)
- ✅ Light, friendly aesthetic (not aggressive dark themes)
- ✅ Professional M&A firm styling
- ✅ Responsive design (mobile-first)
- ✅ Google Maps integration

### Animations & Interactions
- ✅ Partner logo carousel (infinite scroll)
- ✅ Smooth scroll navigation
- ✅ Mobile hamburger menu
- ✅ Hover effects on cards and buttons
- ✅ Form validation
- ✅ Intersection Observer animations

### UX Features
- ✅ Consistent navigation across all pages
- ✅ Active states in navigation
- ✅ Contact form with dropdowns
- ✅ SEO optimized meta descriptions
- ✅ Semantic HTML5 structure

### Technical Excellence
- ✅ Shared CSS (700+ lines) - Brand colors applied
- ✅ Shared JavaScript - Modular, vanilla JS
- ✅ Python HTTP server for development
- ✅ Replit deployment ready
- ✅ No build step required

## 🚀 Quick Deploy to Replit

**Fastest way to deploy:** Clone directly into Replit in 3 commands:

```bash
git clone https://github.com/acg-data/yellowfinequity.git temp
mv temp/* temp/.* . 2>/dev/null || true
rm -rf temp
```

Then click **Run**! Your site is live at port 5000.

For detailed instructions, see [REPLIT.md](REPLIT.md)

## 🎨 Brand Colors

- **EDF0EF** - Primary background (light gray)
- **002355** - Primary text/navy accent
- **FEFEFE** - Card backgrounds, pure white
- **F9D300** - Bright yellow accent

## 📁 Site Structure

```
yellowfin-equity/
├── index.html              # Homepage with hero, stats, process
├── criteria.html           # All 20+ industries overview
├── about.html              # Company story and values
├── contact.html            # Contact form with map
├── css/
│   └── styles.css          # Complete stylesheet with brand colors
├── industries/             # Individual industry pages (20+)
│   ├── b2b-services.html
│   ├── cpg.html
│   ├── dental.html
│   ├── electrical.html
│   ├── environmental.html
│   ├── healthcare.html
│   ├── home-services.html
│   ├── hvac-plumbing.html
│   ├── infrastructure.html
│   ├── insurance.html
│   ├── landscaping.html
│   ├── logistics.html
│   ├── manufacturing.html
│   ├── msp-data.html
│   ├── paving.html
│   ├── pest-control.html
│   ├── restoration.html
│   ├── roofing.html
│   ├── software.html
│   └── veterinarian.html
├── assets/
│   └── images/             # Empty, ready for assets
├── .replit                 # Replit configuration
└── README.md               # This file
```

## 🌟 Features

- **Clean, Professional Design**: Friendly M&A aesthetic (not aggressive PE style)
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- **20+ Industry Pages**: Dedicated pages for each investment criteria
- **Google Maps Integration**: Embedded Austin, TX location map
- **Contact Form**: Complete form with industry and revenue selection
- **Partner Logo Carousel**: Animated scrolling logo section
- **Modern Animations**: Smooth transitions and hover effects
- **SEO Optimized**: Meta descriptions and semantic HTML

## 🏢 Company Info

- **Location**: Austin, Texas
- **Phone**: (512) 348-8082
- **Stats**: Up to $210M EV, 97% LOI to Close, $37B Combined Buying Power
- **Industries**: 20+ including B2B Services, Healthcare, Manufacturing, Software, etc.

## 🛠️ Technical Details

- **Pure HTML/CSS**: No build step required
- **CDN Resources**: Google Fonts, Font Awesome icons
- **No Dependencies**: Runs on any static web server
- **Replit Ready**: Includes `.replit` configuration file

## 📝 Content Highlights

### Key Messages
- "Exceptional buyers for exceptional businesses"
- "No seller fees, just results"
- "Confidentially connecting owners with best-in-class buyers"
- "Respect for your legacy"

### Process Steps
1. Initial Contact
2. Share Your Goals
3. Introduction to Buyers
4. Direct Negotiation
5. Close the Deal

## 🌐 Local Development

If you want to run locally:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000`

## 📱 Pages Overview

### Main Pages
- **Home**: Hero, partner logos, promise, stats, process, deals, map
- **Criteria**: Grid of all 20+ industries with links to detail pages
- **About**: Company story, values, stats, location
- **Contact**: Contact form, info cards, embedded map

### Industry Pages (20+)
Each industry page includes:
- Industry-specific hero section
- Detailed investment criteria checklist
- Call-to-action to schedule appointment
- Navigation back to all industries

## 🎨 Design Philosophy

Unlike traditional PE/M&A sites that use aggressive language like "Sourcing is Broken" and dark themes, Yellowfin Equity uses:

- **Warm, friendly colors**: Light grays and bright yellow accents
- **Positive messaging**: "Exceptional buyers for exceptional businesses"
- **Respectful tone**: Focus on partnership and legacy preservation
- **Clean layout**: Easy to navigate, professional but approachable

## 🔗 Links

- **GitHub**: https://github.com/acg-data/yellowfin-equity
- **Live Site**: [Your Replit URL]

---

**Built with ❤️ for Yellowfin Equity**