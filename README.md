# CHARDA

CHARDA - Charge Determination Analysis
Yaroslav Lyutvinskiy, Amir Ata Saei, Yury Tsybin, Roman Zubarev

Traditionally, mass spectrometry (MS) output is the ion abundance plotted versus ionic mass-to-charge ratio m/z. While employing only commercially available equipment, Charge Determination Analysis (CHARDA) adds a third dimension to MS, estimating for individual peaks their charge states z, starting from z=1, and colour-coding z in m/z spectra. CHARDA combines the analysis of transient decay in Fourier transform (FT) MS with interrogation of mass defects. Being applied to individual isotopic peaks in a complex protein MS/MS dataset, CHARDA facilitates charge state deconvolution of large ionic species in crowded regions, estimating z even in the absence of isotopic distribution (e.g., for monoisotopic mass spectra). CHARDA is fast, robust and consistent with conventional FT MS and FT MS/MS data acquisition procedures. An effective charge resolution Rz≥6 is obtained, with potential for further improvements.

This code is published for article https://chemrxiv.org/engage/chemrxiv/article-details/613a227265db1e3f14b1ab27
"Adding colour to mass spectra: Charge Determination Analysis (CHARDA) assigns charge state to every ion peak"

Currently the article is under review.

Code of CHARDA project is located in /code/CHARDA.ipynb file

Also /code folder containg binaries of publicly available software hardklor (https://proteome.gs.washington.edu/software/hardklor/) working as deisotoping algorytm for CHARDA. 

Charda can be run both on Linux and windows platforms, however setup for Linux platform is easier to reproduce. Corresponding docker file is located in /environment folder. 

Data files for CHARDA were zipped to pass 50Mb limit of github upload. You should unzip them before use.  
