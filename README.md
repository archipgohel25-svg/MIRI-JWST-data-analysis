# MIRI-JWST-data-analysis

This repository contains my work from Summer School 2025 at the India Space Academy.
The project involved identifying spectral lines from James Webb Space Telescope (JWST) Mid-Infrared Instrument (MIRI) data cubes.

## **Project info**
NGC 7469
  - Sky Coordinates : RA - 345.815059 , Dec - 8.873917 
                    Distance – 195+65.6 Mly 
                    Redshift(z) - 0.016268 ± 7.00e-6 
  - Categary – intermediate spiral Galaxy 
  - Seyfert 1 Galaxy :  A type of Active Galactic Nuclei   
- Data: JWST MIRI MRS data cubes (Channels 1–4)

## Tools and Library's 
- Python 3.x
- Astropy
- Matplotlib
- Pandas
- Regions
- SciPy
- NumPy
- ds9 image viewer

## Steps
- download FITS file data from JWST MAST portal for all 4 channels
- Load and inspect FITS cubes
- Apply DS9-defined region masks
- plot wavelength and avg. intensity graph 
- identify and compare spectra lines

## References
- NASA/IPAC Extragalactic Database([NED](https://ned.ipac.caltech.edu/))
- SIMBAD Astronomical Database([SIMBAD](http://cdsxmatch.u-strasbg.fr/))
- JWST MAST portal([MAS](https://archive.stsci.edu/missions-and-data/jwst))
