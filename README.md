# Digital Data Forge (Marketing Site)

Digital Data Forge (Forge) is an infrastructure automation and compliance platform for Ansible, Terraform/OpenTofu, and more. It includes a compliance dashboard, STIG viewer/exports, DoD-focused features, and air‑gap friendly operations.

## Access the Site

- Public website: [digital-data-co.github.io/ddforge](https://digital-data-co.github.io/ddforge/)
- Get Started: [digitaldata.co](https://digitaldata.co)

## What’s in this Repo

Static site pages:
- `index.html` – Home
- `forge-comparison.html` – Feature comparisons vs. common tools
- `thunderdome.html` – DoD Thunderdome readiness details
- `roadmap.html` – Product roadmap
- `supported.html` – Supported platforms, frameworks, and integrations

Documents:
- `docs/DoD_Thunderdome_Analysis.pdf`
- `docs/STIG_Compliance_Report.pdf`

## Local Preview

Open the HTML files directly in a browser, or serve the directory with a simple static server for correct relative links:

```bash
# Example with Python
python3 -m http.server 8080
# Then open http://localhost:8080/
```

## Feedback

Questions or feedback? Visit [digitaldata.co](https://digitaldata.co).
