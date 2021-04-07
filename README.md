# README #


### Summary: ###

Jupyter Notebook & train data for recreating the normative charts from [Dimitrova et al., (2021)](https://academic.oup.com/cercor/advance-article/doi/10.1093/cercor/bhab039/6206863). 
This notebook will allow the user to 

* run Gaussian Process Regression (GPR) on the normative volumetric data provided in ./data/
* fit the model to new test dataset (e.g. mydata.csv & mycov.csv) provided by the user
* calculate Z-scores for the new dataset based on the normative charts
* plot the new dataset overlaid onto the normative charts 

Normative data comprise volumetric measures for 274 term-born infants scanned after birth for the [developing Human Connectome Project](http://www.developingconnectome.org/)
and preprocessed using the official [dHCP structural pipeline](https://github.com/BioMedIA/dhcp-structural-pipeline)  [(Makropoulos et al., 2018)](https://pubmed.ncbi.nlm.nih.gov/29409960/).

*The dHCP imaging data will be publicly available in early 2021. For updates check [here](http://www.developingconnectome.org/second-data-release/).*

-------

### Cite: ###

Please cite the following publication:

Dimitrova, R. et al. "Phenotyping the Preterm Brain: Characterizing Individual Deviations From Normative Volumetric Development in Two Large Infant Cohorts", Cerebral Cortex, (2021), bhab039, https://doi.org/10.1093/cercor/bhab039.

--------

### Dependencies: ###

* python => 3.7 
* [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) 
* numpy
* pandas
* [GPy](https://github.com/SheffieldML/GPy) 
* matplotlib

--------

### Input data: ###

* volumetric data: a csv file with extracted volumes (order shown in *GPR_NeoVolumes.ipynb*)
* covariates: a csv file with PMA at scan & sex

--------

### Running the notebook: ###

* After cloning / downloading the repo, the *GPR_NeoVolumes.ipynb* should be opened and ran in the same working directory. 

--------

### References: ###

Dimitrova, R. et al. "Phenotyping the Preterm Brain: Characterizing Individual Deviations From Normative Volumetric Development in Two Large Infant Cohorts", Cerebral Cortex (2021). [link](https://academic.oup.com/cercor/advance-article/doi/10.1093/cercor/bhab039/6206863)

Makropoulos, A. et al. "The developing human connectome project: A minimal processing pipeline for neonatal cortical surface reconstruction." Neuroimage 173 (2018): 88-112. [link](https://www.sciencedirect.com/science/article/abs/pii/S1053811918300545?via%3Dihub)

------

*Watch this space for further updates.*

------

### License: ###

The data distributed with this work are made available under a [CC-BY 4.0 International license.](https://creativecommons.org/licenses/by/4.0/)



