# Justinianic Plague · Ancient DNA Lab Prototype

⚠ **Prototype Sample** · Demonstrator Only · Not for Research Citation

An experimental interface exploring how archaeological, ancient DNA, and bioarchaeological evidence from the Justinianic Plague (541–750 CE) might be presented interactively — through satellite terrain, 3D specimen models, and multi-proxy narratives.

**Asia Khan, Hon. BA (McMaster University)**  
Behavioral UX Researcher & Design Anthropologist

---

## 🔗 Live Prototype

→ **[View the interactive prototype](https://khan34535-sudo.github.io/justinianic-plague-adna-lab/)**

*(If the link doesn't work, enable GitHub Pages in **Settings → Pages → main branch → / (root)**)*

---

## ⚠ Disclaimer

This is a **design prototype and demonstrator**. It is intended to show how archaeological and paleogenomic information *could* be presented, not to serve as a primary research source.

- ✅ Site names and APA citations point to **real literature**
- ⚠️ Coordinates, dates, and site details are **simplified or approximated**
- ❌ All 3D models, specimen reconstructions, and diagrams are **placeholders**
- ❌ Transmission corridors and spread animation are **illustrative**
- ❌ Numerical indices and scenario outcomes are **conceptual examples**
- **Do not cite this prototype in academic work** — consult original publications

---

## What This Demonstrates

- **Spatial context** — Real satellite imagery with 3D terrain, hosting documented plague sites as spatial anchors
- **Chronological spread** — Animated transmission corridors from Central Asian origin (c. 200 CE) through Pelusium, Constantinople, and outward to extinction (c. 750 CE)
- **3D specimen models** — Procedural Three.js models of molar teeth, petrous bone, *Y. pestis* bacterium, flea vectors, and plague phylogeny
- **Multi-proxy integration** — Ancient DNA, isotopes, osteology, historical texts, and material culture side-by-side
- **Poinar lab workflow** — Six-step ancient DNA pipeline from clean-room sampling to phylogenetic sequencing
- **Readable citations** — Every panel surfaces its own APA 7th reference
- **Contemporary relevance** — Explorable scenarios for COVID-19 parallels and lineage extinction

---

## What's Real vs. Placeholder

| Status | Item |
|--------|------|
| ✅ Real | Site names & regional contexts |
| ✅ Real | APA 7th citations |
| ✅ Real | Archaeological & genomic concepts |
| ✅ Real | Six-step Poinar lab methodology |
| ⚠ Partial | Site coordinates (regional centroids only) |
| ⚠ Partial | Chronological dates (rounded to nearest decade) |
| ❌ Placeholder | All 3D specimen models |
| ❌ Placeholder | Artifact images & diagrams |
| ❌ Placeholder | Transmission corridor geometry |
| ❌ Placeholder | Numerical pandemic indices |
| ❌ Placeholder | Site-level descriptive text |

---

## Running Locally

This prototype is a single self-contained HTML file with no build step required.

1. Download or clone the repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. Navigate using the top tabs
4. Drag 3D models to rotate · Scroll to zoom
5. Click map stars to view site data
6. Press **Play Spread** on the GIS tab to watch the timeline animation

**Note:** The "Find Me" geolocation feature requires the page to be served from a web server or hosted online — it will not work when opened directly from `file://`.

---

## Ethics & Heritage Statement

The sites referenced in this prototype are located on the ancestral and unceded lands of peoples across the Mediterranean and Near East — including the Byzantine Levant, Egypt, Anatolia, Italy, Gaul, and Bavaria.

The individuals buried in the Jerash mass grave and other plague cemeteries were real people who died during a catastrophic pandemic. Any digital presentation of their remains and their history must be done with **respect, attribution, and consultation with descendant and local communities**.

This prototype is a technical demonstration only. It does not claim to speak for any descendant community, and it does not present new archaeological findings.

---

## Tech Stack

- **MapLibre GL JS** — satellite + terrain rendering
- **Esri World Imagery** — free public satellite tiles
- **AWS Terrain DEM** — elevation tiles
- **Three.js r128** — procedural 3D models
- **Tailwind CSS** — layout and styling
- **Google Fonts** — Merriweather (headings) + Inter (body)

---

## Credits

- **Prototype design & development:** Asia Khan, Hon. BA (McMaster University)
- **Scientific framework:** Dr. Hendrik Poinar, McMaster Ancient DNA Centre
- **Design inspiration:** Dr. Shanti Morell-Hart Lab, McMaster University
- **Imagery:** Esri · AWS · OpenStreetMap contributors

### Key Sources Referenced

Full APA 7th citations are embedded throughout the prototype. Foundational sources include:

- Adapa, S. R., et al. (2025). Genetic evidence of *Yersinia pestis* from the First Pandemic. *Genes*, 16(8), 926.
- Wagner, D. M., Klunk, J., Harbeck, M., … Poinar, H. (2014). *Yersinia pestis* and the Plague of Justinian 541–543 AD. *The Lancet Infectious Diseases*, 14(4), 319–326.
- Harbeck, M., et al. (2013). *Yersinia pestis* DNA from skeletal remains from the 6th century AD. *PLoS Pathogens*, 9(5), e1003349.
- Preiser-Kapeller, J., et al. (2025). The circulation of *Yersinia pestis* in Central Eurasia. *Human Ecology*, 53(4), 703–721.
- Vytlačil, Z., et al. (2024). Well supplied in life, set aside in death. *American Journal of Biological Anthropology*, 185(1), e25002.

---

## License

**© 2026 Asia Khan · All Rights Reserved**

This prototype, including its source code, interface design, written content, and procedural 3D models, is the intellectual property of the author. No part of this work may be reproduced, distributed, modified, or transmitted in any form or by any means without prior written permission from the author.

The prototype is provided **"as is"** for demonstration and educational viewing purposes only, without warranty of any kind.

Third-party libraries (MapLibre GL, Three.js, Tailwind CSS, Google Fonts, Font Awesome, Esri imagery, AWS terrain tiles) are used under their respective licenses and remain the property of their original creators.
