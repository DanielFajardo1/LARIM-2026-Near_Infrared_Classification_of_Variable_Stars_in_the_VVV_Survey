**Saturated Stars Morphologies: Addressing Instrumental Artifacts**

In near-infrared astronomical surveys, identifying physical stellar variability requires isolating it from instrumental artifacts. The MINERVA catalog encounters unique structural 
challenges at the bright end of the Ks-band detection threshold (Ks < 11.5 mag), resulting in artificially distorted light curves.

This phenomenon is primarily driven by two factors:
* **Nightly Seeing Variations:** Fluctuating atmospheric conditions alter the point spread function (PSF) from night to night. A bright star might saturate the detector under excellent seeing conditions (where light is tightly focused), but remain unsaturated during poor seeing, creating a high-dispersion pseudo-variability effect.
* **Detector Geometry:** The VIRCAM instrument comprises an array of 16 distinct detector chips (petals). Because each petal has slightly different quantum efficiencies and saturation thresholds, observations of the same star tracking across different petals can trigger sporadic saturation flags.

The resulting morphologies often present truncated peaks (flattened maximum brightness) or extreme, non-physical magnitude scatter. Visualizing these artifacts is crucial for pipeline diagnostics.
