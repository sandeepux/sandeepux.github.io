# Enterprise UX Portfolio

A professional portfolio showcasing enterprise UX design work across security, SaaS products, and complex systems where usability is non-negotiable.

## About

This portfolio highlights work spanning:
- **Research & Discovery** - User research, contextual inquiry, and enterprise workflows
- **Interaction Design** - Platform strategy and interface design for complex applications
- **Design Enablement** - Cross-team collaboration with engineering and product management

## Featured Work

The portfolio features selected case studies from leading organizations:
- **Palo Alto Networks** - Security platform design and team collaboration
- **OpenText** - ILM Policy Builder and enterprise content management
- **Oracle** - Live Experience platform and data solutions

## Project Structure

```
.
├── index.html                           # Main portfolio landing page
├── ndr-dashboard.html                   # NDR case study (OpenText)
├── prisma-cloud.html                    # Prisma Cloud case study (Palo Alto)
├── ilm-policy-builder.html              # ILM case study (OpenText)
├── xdr-platform.html                    # XDR case study (OpenText)
├── oracle-live-experience.html          # Oracle Live Experience case study
├── oracle-unity-platform.html           # Oracle Unity Data Platform case study
├── README.md                            # This file
├── .gitignore                           # Git exclusions (Archive/ folder)
│
├── assets/
│   └── ndr/                             # NDR case study assets
│       ├── anomalies/                   # Anomalies dashboard hi-fi screens
│       ├── rules/                       # Rules builder lo-fi explorations
│       ├── journey/                     # User journey maps
│       └── competitors/                 # Competitive analysis (Azure comparison)
│
├── images/
│   ├── Favicon.png                      # Site favicon
│   ├── Bangalore.jpg                    # Hero image
│   └── bangalore-city-illustration.jpg  # Hero image alt
│
└── Archive/                             # Non-essential files (excluded from deployment)
    ├── Projects_Figma/                  # Figma design files & low-fi sketches
    ├── Work_Pictures/                   # Original photo library
    └── Usecases/                        # PDF case studies (backup)
```

## How to View

### Option 1: Open Directly in Browser
Simply open `index.html` in your web browser.

### Option 2: Local Web Server (Recommended)
To properly load images and assets, use a local web server:

**Using Python 3:**
```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

**Using Node.js:**
```bash
npx serve
```

**Using VS Code Live Server:**
- Install the "Live Server" extension
- Right-click `index.html` and select "Open with Live Server"

## Deployment to GitHub Pages

1. **Create a new repository** on GitHub named `portfolio` or similar
2. **Initialize git** in this directory:
   ```bash
   git init
   ```
3. **Add remote repository:**
   ```bash
   git remote add origin https://github.com/yourusername/portfolio.git
   ```
4. **Add and commit files:**
   ```bash
   git add .
   git commit -m "Initial portfolio deployment"
   ```
5. **Push to GitHub:**
   ```bash
   git push -u origin main
   ```
6. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "GitHub Pages"
   - Select `main` branch as source
   - Your portfolio will be live at `https://yourusername.github.io/portfolio/`

## Design Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Hero Section** - 4 balanced enterprise photography images with CSS filter hover effects
- **Work Card Navigation** - Direct links to individual project pages (not modals)
- **Detailed Case Studies** - Each project has a standalone page with:
  - Strategic context and business goals
  - User research synthesis and interview insights
  - Design evolution from sketches to final design
  - Competitive analysis and positioning
  - Cross-functional influence documentation
  - Validation and outcomes
  - Lessons learned and principal-level thinking
- **Design Assets** - Integrated lo-fi sketches, hi-fi screens, journey maps, and competitive comparisons
- **Intersection Observer API** - Smooth fade-in animations as you scroll
- **Modern Aesthetics** - Clean typography, rounded corners, intentional spacing, professional color palette

## Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Grid layouts, flexbox, filters, and animations
- **Vanilla JavaScript** - Intersection Observer for scroll animations
- **No Dependencies** - Single HTML file with inline CSS and JS

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- All case studies are in PDF format for secure distribution
- Images use CSS filters for optimized performance
- Mobile viewport optimizations for screens under 768px
- Archive folder contains non-essential files and is excluded from deployment

## Contact & Social Links

[Update with your contact information and social profiles in the portfolio]

---

**Last Updated:** April 2026
