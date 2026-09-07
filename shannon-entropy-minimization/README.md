# Minimum Entropy Method: Phase Folding Simulation

**Created by:** Daniel Andrés Fajardo Poveda

This folder contains an interactive demonstration of the Minimum Entropy Method, illustrating how it is utilized to determine the true variability periods of stars within the MINERVA catalog. 
It is designed as a supplementary visual tool for presentations, specifically for the LARIM conference.

## Overview

When analyzing variable star light curves, astronomers test various "trial periods" to fold the time-series data into phase space. The correct physical period minimizes the Shannon entropy of the 
phase-folded light curve. By finding the absolute minimum in the entropy periodogram, we can successfully reconstruct the cleanest, least scattered variability pattern.

This interactive HTML simulation allows users to manually explore the trial period grid and visually experience this entropy minimization process in real-time across different variable star 
classes (CEP-F, RRab, EA, UVAR).

## Features
*   **Interactive Playback:** Animate the trial period scan to watch the entropy valley being traversed while the light curve dynamically reorganizes.
*   **Manual Slider:** Drag the slider to see how microscopic changes in the trial period disrupt or reconstruct the light curve structure.
*   **Snap-to-True-Period:** A quick-action button that instantly aligns the visualization with the deepest entropy minimum (the known catalog period).
*   **Dark Mode Toggle:** Optimized for auditoriums and professional astronomical software aesthetics.
*   **Grouped Selection:** Easily navigate through sample stars categorized by their specific variability class.

*(Note: For the full MINERVA V.1 catalog and other analysis tools, please navigate to the main repository root.)*
