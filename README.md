# Neonatal MRI and infant attachment

Code for analyses presented in: 

Jiménez Sanchez, L., Blesa Cabez, M., Vaher, K., Corrigan, A., Thrippleton, M. J., Bastin, M. E., Quigley, A. J., Fletcher-Watson, S., Boardman, J. P. (2023). "Infant attachment does not depend on neonatal amygdala and hippocampal structure and connectivity". medRxiv, 2023.2012.2007.23299615. https://doi.org/10.1101/2023.12.07.23299615 

Repository author: Lorena Jiménez Sánchez (lorena.jimenezs@ed.ac.uk).


# Directory structure

The project assumes the following file directory system:
- .Rproj.file
- raw_data
- results
	- covariates
	- figures
	- regression
- scripts


# Scripts for data analysis

The repository consists of the folder scripts/ containing Rmarkdown/script files as following:

- MRI_Attachment_dem.Rmd: creating demographic/clinical variables' descriptive tables.
- MRI_Attachment_GM_cov.Rmd: covariate analyses for Amy/Hip structure and attachment behaviours.
- MRI_Attachment_GM_reg.Rmd: regression analyses for Amy/Hip structure and attachment behaviours (untransformed behavioural data).
- MRI_Attachment_GM_reg_transformed.Rmd: regression analyses for Amy/Hip structure and attachment behaviours (transformed behavioural data).		
- MRI_Attachment_WM_cov.Rmd: analyses of covariates for Amy/Hip structural connectivity and attachment behaviours.
- MRI_Attachment_WM_reg.Rmd: regression analyses for Amy/Hip structural connectivity and attachment behaviours (untransformed behavioural data).
- MRI_Attachment_WM_reg_transformed.Rmd: regression analyses for Amy/Hip structural connectivity and attachment behaviours (transformed behavioural data).
	
