# Fraise · Rema Boualdja

Fraise, my personal portfolio site: **https://remaboualdja-coder.github.io** · [LinkedIn](https://www.linkedin.com/in/rema-boualdja-615a4344b/)

Final-year BSc Management student at SOAS University of London, interested in investing, corporate finance and the consumer sector.

## What's here

| Page | What it shows |
|---|---|
| **About** | Background, education, skills |
| **Research** | My equity research on Puig Brands (BME: PUIG): HOLD, €21.75 target. Includes a valuation football field, revenue mix, and a sortable trading-comps table |
| **Live DCF** | My Excel DCF rebuilt to run in the browser. Change growth, margin, cash conversion, WACC or terminal growth and the value per share, cash flows, EV-to-equity bridge and sensitivity table update instantly |
| **Experience** | Roles and projects |

## How it's built

- One static page, `index.html`: HTML, CSS and plain JavaScript, with no frameworks or build step
- Charts are drawn as SVG directly in JavaScript
- Hash-based routing (`#/about`, `#/research`, `#/model` …) so each section has its own link
- Responsive down to phone width
- Hosted free on GitHub Pages

The DCF logic follows the spreadsheet formula by formula. The base case reproduces the Excel output of €21.75 per share.

*Student research for educational purposes, not investment advice. Market data as of 13 November 2026.*
