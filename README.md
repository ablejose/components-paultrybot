# components-paultrybot

Component **datasheet & build reference** for an **Octopus-style autonomous ground robot** for broiler poultry houses — a ground bot that continuously **cleans** (litter scarifying + biocide fogging) and **watches the flock** (health, mortality, environment), 24/7.

It is a single-page website: for each component it explains **what it is, why it is needed, and how it works**, plus diagrams for system architecture, power distribution, control/data flow, and physical layout.

## Live site

Hosted with GitHub Pages: **https://ablejose.github.io/components-paultrybot/**

(If the link 404s right after the first push, wait ~1 minute for the first Pages build to finish.)

## Contents

- `index.html` — the datasheet website (9 subsystems, BOM, build order, diagrams)
- `style.css` — styling
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Subsystems covered

1. Chassis & mobility
2. Drive & motion control
3. Cleaning payload (scarifier + biocide nebuliser)
4. Perception & navigation (LiDAR, RGB/thermal/depth cameras)
5. Environmental sensing (NH3, CO2, temp/RH, PM, litter moisture, mic)
6. Compute & control (Jetson + real-time MCU)
7. Power system (LiFePO4 + BMS + DC-DC + dock)
8. Connectivity (WiFi / 4G)
9. Safety & docking

## Notes

Diagrams render with [Mermaid](https://mermaid.js.org/) via CDN. Example part numbers are illustrative starting points — verify specs and safety ratings before purchase. Not affiliated with Octopus Biosafety.
