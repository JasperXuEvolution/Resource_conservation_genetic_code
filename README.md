# Resource_conservation_genetic_code
This repository contains all the codes to reproduce the manuscript "Is the genetic code optimized for resource conservation?".     
Data:  
Nutrient_metrics.csv: A file contain the carbon, oxygen and nitrogen content for each AAs. The AAs are are represented by their one letter code  
ModelOrganisms.csv: codon frequency data from the paper "A new and updated resource for codon usage tables"  
New_RGC_1e6: A file contain randomized geneitc code information by S&Z's method. Bascially it is a string of number, which correspond to the 4-unit block in the genetic code  
Hurst_1e6: A file contain randomized geneitc code information by conventional method (Haig and Hurst 1991)  
XX_freq.txt: These files are computed codon frequencies in the transcriptome instead of the genome  
XXX_pvalue_dictionary.json: These files are pvalue dictionary files  
Code:  
P_value_calculation_Method1_GH.ipynb: This notebook calculates the nERMC and pvalue of SGC using the S&Z's method for simulating RGCs  
P_value_calculation_Method2_GH.ipynb: This notebook calculates the nERMC and pvalue of SGC using the S&Z's method for simulating RGCs but ignoring the stop codon for calculation  
P_value_calculation_Method2_GH.ipynb: This notebook calculates the nERMC and pvalue of SGC using the Hurst's method for simulating RGCs but ignoring the stop codon for calculation  
Plot: This notebook is used for plotting all the figures except figure 1  
