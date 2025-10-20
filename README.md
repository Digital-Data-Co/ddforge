# Digital Data Forge Website

Marketing and comparison website for Digital Data Forge - Infrastructure Automation & Compliance Platform.

## Pages

### Main Pages
- **`index.html`** - Main landing page with features, comparisons, and CTAs
- **`forge-comparison.html`** - Detailed comparison pages (Semaphore, Tower, Rundeck, GitLab, Jenkins, Spacelift, ConfigOS)
- **`roadmap.html`** - Product roadmap and feature timeline
- **`thunderdome.html`** - DoD Thunderdome readiness analysis (NEW!)

### DoD Thunderdome Page

The **thunderdome.html** page showcases Forge's readiness for DoD Thunderdome and high-security government deployments:

#### Key Sections:
1. **Executive Summary** - 100% DoD-ready status with key compliance metrics
2. **STIG Compliance Certification** - Complete breakdown of 51/51 STIG requirements
3. **Feature Comparison Matrix** - Forge vs typical DoD platforms
4. **8 Unique Advantages** - Features not found in any comparable platform
5. **By The Numbers** - Quantifiable statistics (10+ IaC tools, 1,610 rules, etc.)
6. **DoD Deployment Scenarios** - 4 real-world deployment patterns:
   - Air-Gapped Data Center
   - Kubernetes on JWICS/SIPRNet
   - VMware vSphere Private Cloud
   - Multi-Cloud DoD IL5
7. **Technology Stack** - DoD-approved technologies and standards
8. **Call to Action** - Next steps for DoD evaluation

#### Key Highlights:
- ✅ 100% STIG Compliance (51/51 requirements)
- ✅ FIPS 140-2 Certified
- ✅ 10+ IaC Tools (vs typical 2-3)
- ✅ 7 Official Policy Packs (1,610 compliance rules)
- ✅ Air-Gap Capable with SQLite
- ✅ 8 Unique Features not found elsewhere
- ✅ Purpose-built Reporter role for compliance officers
- ✅ Automated remediation generation

## Features

- **Responsive Design** - Mobile-friendly layouts
- **Dark Mode** - Toggle between light/dark themes (persisted in localStorage)
- **Multi-Language Support** - 11 languages (EN, ES, FR, DE, PT, ZH, JA, IT, RU, KO, AR)
- **Smooth Animations** - CSS transitions and hover effects
- **Modern UI** - Clean, professional design
- **SEO Optimized** - Proper meta tags and descriptions

## Technology Stack

- Pure HTML5/CSS3/JavaScript (no frameworks)
- Responsive CSS Grid layouts
- CSS Variables for theming
- LocalStorage for preferences
- No build step required

## Local Development

Simply open any HTML file in a web browser:

```bash
# Open main page
open index.html

# Open DoD Thunderdome page
open thunderdome.html

# Open comparison page
open forge-comparison.html

# Open roadmap
open roadmap.html
```

## Deployment

This is a static site and can be deployed to:
- GitHub Pages
- Vercel
- Netlify
- Any static hosting service

### GitHub Pages Deployment

```bash
# Ensure you're on the main/master branch
git add .
git commit -m "Update DoD Thunderdome page"
git push origin main

# GitHub Pages will automatically deploy
# Access at: https://digital-data-co.github.io/ddforge/
```

## File Structure

```
ddforge/
├── index.html                  # Main landing page
├── thunderdome.html           # DoD Thunderdome readiness page
├── forge-comparison.html       # Feature comparisons
├── roadmap.html               # Product roadmap
├── favicon.png                # Site icon
└── README.md                  # This file
```

## Content Updates

### Adding a New Comparison
Edit `forge-comparison.html` and add a new tab in the comparison grid.

### Updating DoD Information
Edit `thunderdome.html` - sections are clearly marked with comments.

### Adding Translations
Edit the `i18n` object in each HTML file's `<script>` section.

## Links

- **Main Site**: https://digitaldata.co
- **GitHub**: https://github.com/Digital-Data-Co/forge
- **Documentation**: https://github.com/Digital-Data-Co/forge/blob/develop/DOD_THUNDERDOME_COMPARISON.md
- **STIG Report**: https://github.com/Digital-Data-Co/forge/blob/develop/STIG_COMPLIANCE_FINAL_REPORT.md

## License

MIT License - See main Forge repository for details.

## Contact

For questions about Forge or DoD deployments, contact Digital Data Co. via the main repository.

---

**Last Updated**: October 19, 2025
**Version**: 1.2.0 (Added DoD Thunderdome page)
