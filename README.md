# hi4pi
Whole Sky Galactic Hydrogen Image processing software

Glen Langston - National Science Foundation - 2022 January 11

This project contains tools for smoothing HI4PI images from the
HI4PI collaboration (see https://arxiv.org/abs/1610.06175)/
HI4PI: A full-sky HI survey based on EBHIS and GASS

## Notebook order

These notebooks use an image from the HI4PI collaboration that can be downloaded.  
These low angular resolution images were kindly provided by Dr. Benjamin Winkel
of the Max Planck Insitute for Radio Astronomy.   Two image cubes were provided:

File: hi4pi_1.5deg.fits
* Galactic Coordinates
* Pixel size of 0.5 deg, smoothed to an angular resolution of 1.5 deg 
* The map projection is Plate Caree (FITS/WCS: CAR)
wget ftp://ftp.mpifr-bonn.mpg.de/outgoing/bwinkel/hi4pi_1.5deg.fits

File: langston_eq.fits
* Right Ascension, Declination Coordinates, (J2000)
* Pixel size of 0.5 deg, smoothed to an angular resolution of 1.5 deg 
* The map projection is Plate Caree (FITS/WCS: CAR)
wget ftp://ftp.mpifr-bonn.mpg.de/outgoing/bwinkel/langston_eq.fits

## Noteooks
1. HI4PI-WGET - First download the image.  Note which directory the file is placed.   
2. HI4PI-UPGRADE - Optionally you may need to install/upgrade some Astropy code.  
3. HI4PI-READ - Get and display the galactic coordinate the data.  
4. HI4PI-READ-Equitorial
4. HI4PI-Smooth - Read the data and start processsing the observations.  First we
smooth the image to more closely match observations with horn Radio Telescopes.

### References 

HI4PI Collaboration: N. Ben Bekhti, L. Flöer, R. Keller, J. Kerp, D. Lenz, B. Winkel, J. Bailin, M. R. Calabretta, L. Dedes, H. A. Ford, B. K. Gibson, U. Haud, S. Janowiecki, P. M. W. Kalberla, F. J. Lockman, N. M. McClure-Griffiths, T. Murphy, H. Nakanishi, D. J. Pisano, L. Staveley-Smith

