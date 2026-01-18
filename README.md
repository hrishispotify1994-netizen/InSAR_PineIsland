# InSAR_PineIsland - Wavelength-dependent Sampling of Glacier Flow at Pine Island Glacier
This repository contains the data analysis workflow and reproducible notebooks supporting the study:
“Wavelength-dependent sampling of glacier flow: Implications for internal deformation from multi-sensor InSAR velocities at Pine Island Glacier”
The project investigates how radar wavelength influences the depth over which glacier motion is sampled by InSAR, using Pine Island Glacier (West Antarctica) as a case study. The analysis compares Sentinel-1 C-band ice velocity products with multi-sensor MEaSUREs velocities that incorporate longer-wavelength observations, including L-band SAR.

Scientific Motivation-
InSAR-derived ice velocities are commonly interpreted as surface flow measurements. However, radar wavelength fundamentally controls penetration depth into snow, firn, and ice, implying that different SAR systems may sample motion over different vertical portions of the ice column.
This repository supports a penetration-aware interpretation of InSAR velocities by:
1. Comparing C-band Sentinel-1 velocities with longer-wavelength multi-sensor products
2. Quantifying systematic velocity differences near grounding zones and shear margins
3. Interpreting differences as depth-weighted velocity sampling
4. Discussing implications for future low-frequency (e.g., P-band) SAR missions

Study area - 
Glacier: Pine Island Glacier, West Antarctica
Projection: Antarctic Polar Stereographic (EPSG:3031)
Analysis domain: Fixed rectangular region encompassing the fast-flowing glacier trunk and grounding zone
