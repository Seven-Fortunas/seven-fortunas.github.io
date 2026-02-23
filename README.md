# Seven Fortunas - Company Website

## Overview

Public-facing landing page for Seven Fortunas, showcasing our AI-native enterprise infrastructure and intelligence dashboards.

**Live URL:** https://seven-fortunas.github.io/

---

## Features

### 🎯 Sections

- **Hero**: Mission statement and tagline
- **Dashboards**: Links to all live and upcoming intelligence dashboards
- **What We're Building**: Key infrastructure components
- **Team**: Core team members and AI agents
- **Contact**: GitHub links and partnership info
- **Status**: Current project progress

### 📱 Mobile Responsive

Optimized for all screen sizes:
- Mobile: 320px - 375px
- Tablet: 768px - 1024px
- Desktop: 1024px+

### 🎨 Placeholder Branding

Current design uses placeholder colors and styling. Real Seven Fortunas branding will be applied by Henry during MVP Week (Days 1-3).

**Placeholder Colors:**
- Primary: Deep Blue (#1E3A8A)
- Secondary: Emerald Green (#10B981)
- Accent: Amber (#F59E0B)

---

## Structure

```
seven-fortunas.github.io/
├── index.html          # Main landing page
├── styles.css          # Styling (mobile-responsive)
└── README.md           # This file
```

---

## Dashboard Links

All dashboard links use the pattern: `https://seven-fortunas.github.io/dashboards/{name}/`

**Currently Live:**
- AI Advancements: `/dashboards/ai/`

**Coming Soon:**
- FinTech & DeFi: `/dashboards/fintech/`
- EduTech: `/dashboards/edutech/`
- Security: `/dashboards/security/`
- Opportunities: `/dashboards/opportunities/`

---

## Deployment

### GitHub Pages Configuration

This repository uses GitHub Pages to serve the static website:

1. **Source**: Deploy from `main` branch, root directory
2. **Custom Domain**: (Optional) Can be configured later
3. **HTTPS**: Automatically enabled by GitHub Pages

### Deployment Process

Any push to `main` branch automatically deploys via GitHub Pages:

```bash
git add index.html styles.css
git commit -m "Update landing page"
git push origin main
```

Changes typically appear within 1-5 minutes.

---

## Local Development

To test locally:

```bash
# Option 1: Python HTTP server
python3 -m http.server 8000

# Option 2: PHP server
php -S localhost:8000

# Then open: http://localhost:8000
```

---

## Feature Implementation

**Feature ID:** FEATURE_057 - Company Website Landing Page

**Requirements Met:**
- ✅ Static HTML/CSS landing page
- ✅ Hero/mission section
- ✅ Links to all dashboards
- ✅ About/team section
- ✅ Contact section
- ✅ Mobile-responsive (320px, 768px, 1024px breakpoints)
- ✅ Placeholder branding
- ✅ README documentation

**Verification:**
```bash
# Check files exist
test -f index.html && test -f styles.css && test -f README.md

# Verify mobile breakpoints in CSS
grep -c "@media.*320px" styles.css
grep -c "@media.*768px" styles.css

# Test dashboard link
curl -I https://seven-fortunas.github.io/dashboards/ai/
```

---

## Future Enhancements

### Real Branding (Days 1-3)
- Replace placeholder colors with Seven Fortunas brand colors
- Add logo and visual identity
- Custom fonts and typography

### Content Updates
- Team photos and detailed bios
- Case studies and success stories
- Blog/news section

### Interactive Features
- Newsletter signup
- Contact form
- Live chat integration

---

## Related Repositories

- **Brain**: [seven-fortunas-brain](https://github.com/Seven-Fortunas/seven-fortunas-brain) - Knowledge management
- **Dashboards**: [dashboards](https://github.com/Seven-Fortunas/dashboards) - Intelligence platforms
- **Infrastructure**: [7f-infrastructure](https://github.com/Seven-Fortunas/7f-infrastructure) - DevOps automation

---

## License

© 2026 Seven Fortunas. All rights reserved.

---

## Changelog

### 2026-02-23 - FEATURE_057 Implementation
- Created landing page with all required sections
- Mobile-responsive design with 320px, 375px, 768px breakpoints
- Dashboard links to all 7F Lens platforms
- Team and contact sections
- Placeholder branding with clear notices

### 2026-02-12 - Initial Version
- Basic hero and mission sections
- Preliminary content structure
