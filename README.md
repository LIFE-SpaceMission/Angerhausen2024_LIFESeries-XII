
# Large Interferometer For Exoplanets (LIFE). XII. The Detectability of Capstone Biosignatures in the Mid-infrared—Sniffing Exoplanetary Laughing Gas and Methylated Halogens
  

Spectra with and without CH3X and N2O for various planetary cases and stars used in the LIFE XII paper (Angerhausen D., Pidhorodetska D., Leung M., Hansen J., Alei E., Dannert F., Kammerer J., et al., 2024, AJ, 167, 128, 10.3847/1538-3881/ad1f4b)

Link to paper: 	https://iopscience.iop.org/article/10.3847/1538-3881/ad1f4b

  
  

  

## Description of the different subdirectories:  

  
  

- `CH3X/`  

	Contains the spectra with and without CH3X for various stars (Figure 3). Files are labeled based on their star:
	- `out_adl`: AD Leonis
	- `out_K6V`: K6V star 
	- `out_pcb`: Proxima Centauri
	- `out_t1e`: Trappist-1 
	Each file contains: Wl [wavelength, in microns] and Spectral Radiance [W/sr/m2/um] at varying abundances of Cl, Br, and both. Columns are labeled as: No molecule (no molecule in the spectrum), 1x, 10x, 100x molecule (1, 10, 100 times the molecule abundance.)

  

- `N2O/` 

	
	Contains the spectra with and without N2O for various stars (Figure 2). Files are labeled based on their star:
	- `sun_updatedclouds`: Sun
	- `k6v_updatedclouds`: K6V star 
	- `proxcen_updatedclouds`: Proxima Centauri
	- `trappist_updatedclouds`: Trappist-1 
	Each file contains: Wavelegnth [microns] and Spectral Radiance [W/sr/m2/um] at varying abundances of N2O. Columns are labeled as: NoN2O (no N2O in the spectrum), 1Tmol, 10Tmol, 100Tmol molecule (1, 10, 100 Teramol/yr N2O.)
  

> **Note:** The Jupyter notebook  [conversion.ipynb](conversion.ipynb) allows you to convert to LIFEsim-friendly units to reproduce the Figures in the paper. 
