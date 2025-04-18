# Photometric Analysis and Visualization of Transiting Exoplanets (CoRoT-2b Case Study)

**Sponsored by Xcel Energy and Ball Aerospace**


**[Link to Live Demo](https://nthn.space/exoplanet)**

![Scholarly Research Poster Preview](./NTScholarlyResearchPosterPreview%20(2).png)

## Overview

This repository showcases a project that merges the scientific photometric analysis of the exoplanet CoRoT-2b with an interactive 3D visualization tool designed to demonstrate the principles of transit photometry. The study focuses on CoRoT-2b’s transit, deriving key planetary parameters from observational data, while the visualizer provides a real-time, interactive simulation of the CoRoT-2 system (along with a representation of Gaia BH1) using orbital mechanics and advanced rendering techniques.

## Table of Contents

*   [Overview](#overview)
*   [Exoplanet Transit Photometry Visualizer](#exoplanet-transit-photometry-visualizer)
    *   [Live Demo](#live-demo)
    *   [Features](#features)
    *   [Technology Stack](#technology-stack)
    *   [Running the Visualizer](#running-the-visualizer)
*   [Photometric Analysis of CoRoT-2b](#photometric-analysis-of-corot-2b)
    *   [Methodology](#methodology)
    *   [Key Findings](#key-findings)
*   [Changelog](#changelog)
*   [Contributing](#contributing)
*   [Acknowledgements](#acknowledgements)
*   [License](#license)
*   [References](#references)
*   [Creator](#creator)

## Exoplanet Transit Photometry Visualizer

An interactive 3D simulation demonstrating the principles of exoplanet detection using transit photometry. Visualize the CoRoT-2 system (with a representation of Gaia BH1) using real-time rendering and orbital mechanics calculations.

### Live Demo

[Link to Live Demo]

### Features

*   **Real-time 3D Visualization:** Renders planets, stars, comets, and effects using Three.js.
*   **Transit Photometry Simulation:** Shows the dip in stellar brightness (light curve) during planetary transits, illustrating the concepts used in the analysis.
*   **Accurate Orbital Mechanics:** Calculates planetary positions using Keplerian algorithms.
*   **Procedural GLSL Shaders:** Custom shaders generate dynamic star surfaces with limb darkening, planetary atmospheric glow, detailed skybox/nebulas, comet tails, and an artistic black hole accretion disk.
*   **Interactive Controls:** Allows camera manipulation (rotate, zoom, pan), time scale adjustment, object selection/following, and view jumping (e.g., Gaia BH1).
*   **Responsive UI:** Adapts information panels and controls to various screen sizes.

### Technology Stack

*   **Frontend:** HTML, CSS, JavaScript
*   **3D Rendering:** Three.js (r128)
*   **Shaders:** GLSL
*   **Framework (Hosting):** Next.js / React (as part of the larger portfolio project)

### Running the Visualizer

1.  Clone the repository.
2.  Install dependencies: `npm install` (or `yarn install`)
3.  Run the development server: `npm run dev` (or `yarn dev`)
4.  Open your browser to `http://localhost:3000` (or the specified port).
5.  Navigate to the `/exoplanet` page (or access `public/exoplanet-visualizer.html` directly if structured that way).

## Photometric Analysis of CoRoT-2b

This section details the methodology and findings from the photometric analysis of observational data for the exoplanet CoRoT-2b.

### Methodology

*   **Data Acquisition & Photometry:**
    *   **Observations:** Data were captured using CCD cameras on telescopes located in Australia, Spain, New Mexico, and California. Exposures of 300 seconds were used during transit events.
    *   **Tools:** VPhot was employed for data reduction and extracting magnitude measurements.
    *   **Magnitude Measurements:**
        *   Out‑of‑Transit Average: ≈ 12.427 (σ ≈ 0.01549)
        *   In‑Transit Average: ≈ 12.475 (σ ≈ 0.01153)
        *   Combined Overall Average: ≈ 12.451 (σ ≈ 0.01351)

*   **Analytical Approach:**
    *   **Background:** Classical photometric methods were merged with modern analysis by comparing light curves obtained before, during, and after the transit event to deduce planetary parameters.

### Key Findings

*   **Characteristics:** CoRoT‑2b is identified as a "hot Jupiter," estimated to be approximately 1.5 times larger and 3.5 times more massive than Jupiter.
*   **Transit Depth:** The observed transit depth was roughly 32%, providing critical insights into the planet’s relative size and orbital characteristics.
*   **Data Quality:** The analysis utilized high-quality images with Signal-to-Noise Ratio (SNR) errors below 0.005, confirming the robustness of the measurements.

## Contributing

Contributions are welcome! For guidelines on improving the data analysis, visualization, or documentation, please see `CONTRIBUTING.md`.

## Acknowledgements

Special thanks to **Xcel Energy** and **Ball Aerospace** for their sponsorship and valuable support in advancing this research and visualization project in exoplanet photometry.

## License

This project, including the analysis methodology, results, and the visualization code, is presented solely for demonstrative purposes of the work completed by the creator. It is not available for reuse, reproduction, modification, or distribution.

**All Rights Reserved.**

## References

*(References cited in the original photometric analysis study)*

*   Types of Variables | AAVSO. AAVSO. Web. 28 June 2015. `https://www.aavso.org/types-variables`
*   SCIENCE & TECHNOLOGY. PlanetQuest. Web. 28 June 2015. `http://planetquest.jpl.nasa.gov/page/history`
*   Transit Photometry. The Planetary Society Blog. Web. 28 June 2015. `https://www.planetary.org/articles/transit-photometry`
*   NASA. NASA. Web. 28 June 2015. `https://www.nasa.gov`
*   NASA Exoplanet Archive. NASA Exoplanet Archive. Web. 28 June 2015. `https://exoplanetarchive.ipac.caltech.edu`
*   NASA Kepler. NASA. Web. 28 June 2015. `https://www.nasa.gov/mission_pages/kepler/main/index.html`
*   Guide to CCD Photometry. Photometry Guide. Cambridge: AAVSO, 2014. 1‑82. Print. `https://www.aavso.org/sites/default/files/ccd_photometry_guide/CCDPhotometryGuide.pdf`
*   Online Photometry – Remote Internet Telescope Network – Online Imaging & Telescope Hosting Service. Web. 1 July 2015. `https://www.itelescope.net/`
*   Photometrica Tutorial 1, Introduction. Kenmogul's Library. Web. 1 July 2015. `https://www.screencast.com/users/kenmogul/folders/Default/media/f5ae741d-404e-4e18-bf28-b0aedbc23d8`
*   CoRoT‑2a: Star Blasts Planet With X‑rays [Photograph]. (2011). Retrieved from `http://chandra.harvard.edu/photo/2011/corot/corot_lg.jpg`

## Creator

Created by **nthncyz**
[https://github.com/nthncyz](https://github.com/nthncyz)
