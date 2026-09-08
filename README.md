# Simulate and Explore MINERVA Catalogue

Welcome! This repository contains the resources and supplementary materials for my LARIM presentation. Please select the material you wish to explore using the quick links below, or scroll down for detailed overviews and usage instructions for each tool.

## Quick Access Links
* **[📄 Download Slides](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/slides-and-poster/LARIM_2026_Slides.pdf)**
* **[📄 Download Poster](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/slides-and-poster/LARIM_2026_Poster.pdf)**
* **[▶ Launch Interactive Minimum Entropy Simulation](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/shannon-entropy-minimization/simulacion_larim.html)**
* **[▶ Launch Interactive Parameter Space Explorer](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/parameter-space-explorer/minerva_parameter_space.html)**
* **[📁 View MINERVA V.1 Catalog (FITS Files)](https://github.com/DanielFajardo1/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/tree/main/minerva-v1)**

*(Note: The interactive simulation runs entirely in your web browser; no installation is required).*

---

## LARIM 2026 Presentations 

This section contains the digital poster presented at the LARIM conference, alongside the presentation slides. These materials provide a deeper dive into the methodology and expanded
results of the research. This work corresponds to the Master's thesis of Daniel Fajardo-Poveda at Universidad de los Andes, in co-authorship with Alejandro Garcia.

**Access the Materials**
* **[📄 Download Slides (PDF)](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/slides-and-poster/LARIM_2026_Slides.pdf)**
* **[📄 Download Poster (PDF)](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/slides-and-poster/LARIM_2026_Poster.pdf)**

---

## Minimum Entropy Method: Phase Folding Simulation

**Created by:** Daniel Andrés Fajardo Poveda

This interactive demonstration illustrates how the Minimum Entropy Method is utilized to determine the true variability periods of stars within the MINERVA catalog. It is designed as a supplementary visual tool for presentations, specifically for the LARIM conference.

When analyzing variable star light curves, astronomers test various "trial periods" to fold the time-series data into phase space. The correct physical period minimizes the Shannon entropy of the phase-folded light curve. By finding the absolute minimum in the entropy periodogram, we can successfully reconstruct the cleanest, least scattered variability pattern.

This interactive HTML simulation allows users to manually explore the trial period grid and visually experience this entropy minimization process in real-time across different variable star classes (CEP-F, RRab, EA, UVAR).

**Features**
*   **Interactive Playback:** Animate the trial period scan to watch the entropy valley being traversed while the light curve dynamically reorganizes.
*   **Manual Slider:** Drag the slider to see how microscopic changes in the trial period disrupt or reconstruct the light curve structure.
*   **Snap-to-True-Period:** A quick-action button that instantly aligns the visualization with the deepest entropy minimum (the known catalog period).
*   **Dark Mode Toggle:** Optimized for auditoriums and professional astronomical software aesthetics.
*   **Grouped Selection:** Easily navigate through sample stars categorized by their specific variability class.

**Access the Simulation**
* **[▶ Launch Interactive Minimum Entropy Simulation](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/shannon-entropy-minimization/simulacion_larim.html)**

---

## Interactive Parameter Space Explorer

The MINERVA catalog categorizes near-infrared variable stars into two primary physical groups: **Radial Pulsators** and **Eclipsing Binaries**. Radial pulsators, such as Fundamental 
Cepheids (CEP-F) and RR Lyrae (RRab, RRc), are intrinsic variables that physically expand and contract, producing distinct, often asymmetric periodic variations in brightness. Eclipsing 
binaries (EA, EB, EW) are extrinsic variables consisting of two stars orbiting a common center of mass; their apparent brightness drops when one component blocks the light of the other, 
creating light curves defined by primary and secondary eclipses. 

To effectively separate these populations, the classification framework evaluates several physical and statistical metrics:

* **Period (d):** The time required to complete one full variability cycle.
* **Amplitude (mag):** The difference between the maximum and minimum Ks-band brightness, calculated robustly using the 2nd and 98th percentiles.
* **Symmetry Factor:** Evaluates light curve phase morphology by measuring the phase difference between minimum brightness and subsequent features, providing a direct physical metric of asymmetry.
* **R21_Fourier:** The amplitude ratio of the first and second Fourier harmonics, highlighting structural light curve differences.
* **Phi21_Fourier (rad):** The phase difference between the first two harmonics, crucial for separating different pulsator sub-classes like RRab and RRc.
* **Skewness & Kurtosis:** Statistical moments describing the asymmetry and tailedness of the magnitude distribution.
* **Eclipse Depth Ratio:** The ratio between the depths of the primary and secondary eclipses, essential for distinguishing contact (EW) from detached (EA) binary systems.

*Preliminary Results Disclaimer: The MINERVA developers are currently fine-tuning the multi-class classification algorithms to maximize accuracy across all near-infrared datasets. The data 
visualized in this interactive explorer represents a preliminary preview of the catalog's ongoing structural tuning.*

* **[▶ Launch Interactive Parameter Space Explorer](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/parameter-space-explorer/minerva_parameter_space.html)**

---
## MINERVA V.1 Catalog

**Overview**
*(Space reserved to add a brief description of the MINERVA catalog, such as its construction, data sources, and variable star classifications).*

**Access the Catalog**
* **[📁 View MINERVA V.1 Catalog (FITS Files)](https://github.com/DanielFajardo1/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/tree/main/minerva-v1)**

---
