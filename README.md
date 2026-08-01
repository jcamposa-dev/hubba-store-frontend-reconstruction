# Hubba Store - Front-End Reconstruction Project

A high-performance, responsive front-end reconstruction of a legacy e-commerce platform, migrating historical data from automated database snapshots into modern, clean, and semantic HTML5/CSS3 components.

## 📌 Project Overview
This project bridges commercial business logic with modern web standards. It takes the legacy data architecture of **Hubba Skate & Surf**, a retail business that operated in Costa Rica for over a decade, and reconstructs its UI/UX from the ground up using a modular component approach.

* **Legacy Source Baseline:** Historical data recovered via the [Wayback Machine Archive](https://archive.org).
* **Primary Objective:** Optimize the front-end layout for fast rendering in regions with limited connectivity, reducing layout shift and removing unoptimized automated code overhead.

---

## 🛠️ Tech Stack & Engineering Standards
* **Structure:** Clean HTML5 Semantic Architecture (`<article>`, `<section>`, `<nav>`).
* **Performance:** Implemented `loading="lazy"` native asset management to lower data consumption on mobile connections.
* **Accessibility (a11y):** Integrated ARIA labels (`aria-label`, `role="status"`) to ensure data visibility for screen readers, specifically targeting price adjustments and commercial discounts.
* **Version Control:** Managed via strict Git branching strategy and industry-standard documentation tracking.

---

## 📁 Repository Structure
```text
hubba-store-frontend-reconstruction/
 ├── index.html                 # Main entry point (Clean Reconstructed Home)
 ├── README.md                  # Project documentation and engineering process
 │
 ├── components/                # Modular UI/UX clean components
 │    └── tarjeta-producto.html # Refactored semantic product showcase
 │
 └── legacy-source/             # Historical data and reverse-engineering blueprints
      ├── hubba-raw.html        # Raw HTML recovered from historical server logs
      └── antes-wayback.png     # Full-size layout capture of the source baseline
```

---

## 💼 Business & UX Rationale Behind the Code
Unlike generic coding exercises, this repository reflects an acute understanding of **conversion rate optimization (CRO)** and profit margins:
1. **Friction Reduction:** The interface layout is engineered to support a streamlined 2-step checkout funnel.
2. **Data Structure Hierarchy:** Brand alignment, pricing contrast, and action triggers are positioned based on pattern-recognition workflows to minimize cognitive fatigue and user drop-off.
3. **SEO Readiness:** Semantically marked headings ensure search engines can properly parse brand-product relationships instantly.
