# Exoplanet Transit Photometry Visualizer

Interactive 3D simulation demonstrating the principles of exoplanet detection using transit photometry. 
Visualize the CoRoT-2 system (with a representation of Gaia BH1) using real-time rendering and orbital mechanics calculations.

**[Link to Live Demo](https://nthn.space/exoplanet)**

## Features

*   **Real-time 3D Visualization:** Renders planets, stars, comets, and effects using Three.js.
*   **Transit Photometry Simulation:** Shows the dip in stellar brightness (light curve) during planetary transits.
*   **Accurate Orbital Mechanics:** Calculates planetary positions using Keplerian algorithms.
*   **Procedural GLSL Shaders:** Custom shaders generate:
    *   Dynamic star surfaces with limb darkening.
    *   Planetary atmospheric glow.
    *   Detailed skybox and background nebulas.
    *   Comet tails and an artistic black hole accretion disk.
*   **Interactive Controls:** Allows camera manipulation (rotate, zoom, pan), time scale adjustment, object selection/following, and view jumping (e.g., Gaia BH1).
*   **Responsive UI:** Adapts information panels and controls to various screen sizes.

## Technology Stack

*   **Frontend:** HTML, CSS, JavaScript
*   **3D Rendering:** Three.js (r128)
*   **Shaders:** GLSL
*   **Framework (Hosting):** Next.js / React (as part of the larger portfolio project)

## Running the Visualizer

1.  Clone the repository.
2.  Install dependencies: `npm install` (or `yarn install`)
3.  Run the development server: `npm run dev` (or `yarn dev`)
4.  Open your browser to `http://localhost:3000` (or the specified port).
5.  Navigate to the `/exoplanet` page (or access `public/exoplanet-visualizer.html` directly).

## License

All Rights Reserved.

---

*Created by nthncyz*
https://github.com/nthncyz
