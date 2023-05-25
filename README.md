# 451InGaAsSb_absorption_data
The absorption spectra of different alloy fractions of InGaAsSb is presented

The exact alloys with alloy fractions x are: 
  (GaSb)x(InAs0.91Sb0.09)(1-x)
These relative fractions are chosen to maximize lattice matching

These are presented as csv files generated from python.pandas dataframes. 

The first row of the CSV files corresponds to the column names. 

A B S O R P T I O N   A N D   T R A N S M I S S I O N 
The first column corresponds to the wavelength for the absorption and transmission spectra 
A normalization correction is applied to some of the samples, leading to the sperate correction of normalizing the transmission to 1. 
This is due to the rough substrate side of the samples leading to not all the light reaching the detector. 

T E M P E R A T U R E  A N D  A B S O R P T I O N 
The file names correspond to the  Indium alloy fraction of InGaAsSb ex: Eg In005GaAsSb corresponds to 0.05 Indium
The first column for the temperature absorption spectra corresponds to photon energy measured in eV
