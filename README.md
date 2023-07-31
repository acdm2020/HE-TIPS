# HE-TIPS

Code used for analysis of untargeted metabolomics data from peripheral and hepatic vein blood to determine signatures for the development of hepatic encephalopathy (HE).

## Instructions on Data Access
Untargeted metabolomics data is available on MassIVE database [https://massive.ucsd.edu/] under the MassIVE ID MSV000090443.
Feature based molecular networking data is available on GNPS https://gnps.ucsd.edu/ProteoSAFe/status.jsp?task=8068b7cb58f2465f97a15b3ce30d593c.

## Organization of files

### Input data
All data used for analysis is available under `./data`

### Data Analysis
There are 4 main files that contain several analysis steps for this project under `./code` :

- `deicode.sh` - code and analysis used for parts of figures 1-2.
- `main_Fig1-2.R` - code and analysis used for generating results and figures 1-2.
- `main_Fig3-5.R` -  code and analysis used for generating results and figures 3-5.
- `function_lcms.R` - functions used in main R files.


## Citation
Pre- and Post-Portosystemic Shunt Placement Metabolomics Reveal Molecular Signatures for the Development of Hepatic Encephalopathy 
Ana Carolina Dantas Machado1, Stephany Flores Ramos, Julia M. Gauglitz, Anne-Marie Fassler, Daniel Petras, Alexander A. Aksenov, Un Bi Kim,
Michael Lazarowicz, Abbey Barnard Giustini, Hamed Aryafar, Irine Vodkin, Curtis Warren, Pieter C. Dorrestein, Ali Zarrinpar, Amir Zarrinpar
medRxiv 2023.01.02.22281374; doi: https://doi.org/10.1101/2023.01.02.22281374
