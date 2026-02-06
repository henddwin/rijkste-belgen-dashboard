# De Rijkste Belgen — Lead Dashboard

Interactive dashboard combining data on Belgium's wealthiest families, their companies, and key contacts.

## Data

- **689 families** ranked by wealth (source: derijkstebelgen.be)
- **1,560 companies** extracted from family profiles (many-to-many)
- **367 people** with verified emails via Apollo enrichment

## Usage

Open `index.html` in a browser. All data is loaded from JSON files in `data/`.

### Features

- 🔍 Full-text search across all tabs
- 👑 Families tab with wealth ranking, expandable detail rows showing linked companies & people
- 🏢 Companies tab with family linkage
- 👤 People tab with LinkedIn profiles and email addresses
- 📊 Dropdown filters for family, company, and minimum wealth
- 📱 Responsive design

## Live

Deployed via GitHub Pages: https://henddwin.github.io/rijkste-belgen-dashboard/

## Stack

Single HTML file — Tailwind CSS, Lucide icons, vanilla JS. No build step.
