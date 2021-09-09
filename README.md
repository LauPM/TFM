# Master's Final Project to access the Master in Particle Physics and Physics of the Cosmos (IFCA-UC) 


## Author: Laura Pérez Molina

### Title: Obtaining temperature maps of the CMB anisotropies, correlated and uncorrelated with polarization

### Supervisors: Patricio Vielva y Elena de la Hoz López Collado



The main idea of the protect is to analyse whether the correlated temperature CMB maps with polarization (or vice-versa) allow us to draw more significant conclusions on the CMB detected anomalies rather than the original temperature and polarization CMB maps. For this purpose we study the optimal techniques to obtain these CMB correlated maps. (see the <a href="https://laupm.github.io/TFM-Correlated_CMB_maps/PerezMolinaLaura_TFM.pdf">memoir</a> for more information )


The complete code can be found at: https://laupm.github.io/TFM-Correlated_CMB_maps/TFM_Correlated_CMB_maps.html

#### Erratum

  - We have found that there is an error in the determination of the optimal degrees of the mask apodization, in the first version we have uploaded the result was 5 degrees but repeating the procedure 2 degrees is obtained. This error seems to solve the "divergence" at low \ell values that appears when the angular power spectra is computed with NaMaster.
  - The dispersion table where foreground residuals are included need to be re-run to get coherent results according to the foreground level invluded. Not only that but may be it is necesary to rethink the "ideal" map which is used to compare as we do not include foreground residuals and this could increase the computed dispersion.
  - I will try to update more possible errors :)
