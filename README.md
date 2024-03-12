# Neonatal MRI and infant attachment

Code to reproduce the analyses presented in: "Infant attachment does not depend on neonatal amygdala and hippocampal structure and connectivity".

Repository author: Lorena Jiménez Sánchez (lorena.jimenezs@ed.ac.uk).

# Directory structure

The project assumes the following file directory system:

- .Rproj.file
	- raw_data
	- results
		- covariates
		- demographics
		- figures
		- regression
		- reliability
	- scripts

# Scripts for data analysis

The repository consists of the following folder:

- scripts/ containing Rmarkdown/script files as following:


	- MRI_Attachment_dem.Rmd: demographic/clinical variables' descriptive tables, comparison of demographic characteristics between the included and excluded sample, and correlations of attachment behaviours.
	- 	MRI_Attachment_GM_cov.Rmd: covariate analyses for Amy/Hip structure and attachment behaviours.
	- MRI_Attachment_GM_reg_nologit.Rmd: regression analyses for Amy/Hip structure and attachment behaviours (untransformed behavioural data).
	- MRI_Attachment_GM_reg_logit.Rmd: regression analyses for Amy/Hip structure and attachment behaviours (transformed behavioural data).		
	- MRI_Attachment_GM_reg_logit_sens.Rmd: sensitivity regression analyses for Amy/Hip structure and attachment behaviours (transformed behavioural data).		
	- MRI_Attachment_WM_cov.Rmd: analyses of covariates for Amy/Hip structural connectivity and attachment behaviours.
	- MRI_Attachment_WM_reg_nologit.Rmd: regression analyses for Amy/Hip structural connectivity and attachment behaviours (untransformed behavioural data).
	- MRI_Attachment_WM_reg_logit.Rmd: regression analyses for Amy/Hip structural connectivity and attachment behaviours (transformed behavioural data).
	- MRI_Attachment_WM_reg_logit_sens.Rmd: sensitivity regression analyses for Amy/Hip structural connectivity and attachment behaviours (transformed behavioural data).
	- MRI_Attachment_inter_rel.Rmd: inter-rater reliability analyses for attachment behaviours.	
	- MRI_Attachment_intra_rel.Rmd: intra-rater reliability analyses for attachment behaviours.
