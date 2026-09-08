**Interactive Parameter Space Explorer**

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

* **[▶ Launch Interactive Parameter Space Explorer](https://danielfajardo1.github.io/LARIM-2026-Near_Infrared_Classification_of_Variable_Stars_in_the_VVV_Survey/parameter-space-explorer/minerva_parameter_space.html)**
