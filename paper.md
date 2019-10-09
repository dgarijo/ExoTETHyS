---
title: 'ExoTETHyS: Tools for Exoplanetary Transits around host stars'
tags:
 - python
 - astronomy
 - exoplanets
 - exoplanetary transits
 - stellar limb-darkening
authors:  
 - name: Giuseppe Morello  
   orcid: 0000-0002-4262-5661  
   affiliation: 1, 2, 3  
 - name: Antonio Claret    
   affiliation: 4, 5  
 - name: Marine Martin-Lagarde   
   affiliation: 1  
 - name: Christophe Cossou   
   affiliation: 6  
 - name: Angelos Tsiaras   
   affiliation: 3  
 - name: Pierre-Olivier Lagage    
   affiliation: 1    
affiliations:  
 - name: AIM, CEA, CNRS, Université Paris-Saclay, Université Paris Diderot, Sorbonne Paris Cité, F-91191 Gif-sur-Yvette, France  
   index: 1  
 - name: INAF, Osservatorio Astronomico di Palermo, Piazza del Parlamento 1, 90134 Palermo, Italy  
   index: 2  
 - name: Dept. of Physics & Astronomy, University College London, Gower Street, WC1E 6BT London, UK  
   index: 3  
 - name: Instituto de Astrofísica de Andalucía, CSIC, Apartado 3004, 18080 Granada, Spain  
   index: 4  
 - name: Dept. Física Teórica y del Cosmos, Universidad de Granada, Campus de Fuentenueva s/n, 10871, Granada, Spain  
   index: 5  
 - name: Institut d'Astrophysique Spatiale, CNRS/Université Paris-Sud, Université Paris-Saclay, bâtiment 121, Université Paris-Sud, 91405, Orsay Cedex, France  
   index: 6
 date: 8 October 2019  

 ---

#Summary 
 
Software URL: <https://github.com/ucl-exoplanets/ExoTETHyS>

ExoTETHyS is a python2/3 package which aims to provide a stand-alone set of tools for modeling spectro-photometric observations of the transiting exoplanets. Now, it contains the following subpackages:  
1. SAIL (Stellar Atmosphere Intensity Limb), i.e., a calculator of stellar limb-darkening coefficients that outperforms the existing software by one order of magnitude in terms of light-curve model accuracy, i.e., down to <10 parts per million (ppm);  
2. TRIP (Transit Ring-Integrated Profile), which can compute an exact transit light-curve by direct integration of the occulted stellar flux from the model intensities, without using a parameterization (limb-darkening law) to approximate the stellar intensity profile.

More details are contained in a companion paper (arXiv:1908.09599, under review) and in the technical documentation on GitHub. The package is currently being used with synthetic data in order to assess the overall uncertainty in exoplanet spectra obtained with the JWST and ARIEL instruments, including the uncertainties in the measured stellar parameters and in the stellar models. It is also being used for the analysis of real exoplanetary transits. Another project is the empirical validation of stellar limb-darkening models through the analysis of high-precision photometric observations obtained, in particular, with Kepler, K2, TESS, CHEOPS and PLATO.


#Acknowledgments  
G. M., M. M.-L. and P.-O. L. were supported by the LabEx P2IO, the French ANR contract 05-BLANNT09-573739 and the European Unions Horizon 2020 Research and Innovation Programme, under Grant Agreement N 776403. G.M. also acknowledges the contribution from INAF through the "Progetto Premiale: A Way to Other Worlds" of the Italian Ministry of Education, University, and Research. 
A.C. acknowledges financial support from the Spanish MEC (AYA2015-71718-R and ESP2017-87676-C5-2-R), the State Agency for Research of the Spanish MCIU through the "Center of Excellence Severo Ochoa" award for the Instituto de Astrofísica de Andalucía (SEV-2017-0709). 