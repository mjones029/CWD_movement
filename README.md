# CWD_movement
This repository contains representative code for key analyses in the manuscript, "Malady in motion: Chronic wasting disease effects on host movement."  

This repository will be versioned and archived with Zenodo, upon manuscript acceptance.

All code includes RMarkdown scripts with HTML outputs so users can see analyses in context. Most data for this manuscript is not publicly available*, so the HTML files help document methods in light of this.  

To view an RMarkdown report HTML, click on the report of interest within the "Markdown_reports" folder. Within the page for that report, click on the download button highlighted by the red arrow in the below picture:  
![](https://drive.google.com/uc?export=view&id=1PZK43_5SMw-nS8adklb2E-Bu3-1zXyUX)

Once downloaded, just click on the downloaded file and the HTML should appear in your web browser.  

### What's inlcuded in this repository:

1. Simulation-based approach for matching case-control pairs: **Case_control_pairing**  
2. Conditional logistic regressions for movement metrics: **Conditional_logReg**  
3. Changepoint analysis of movement metrics: **Movement_cp**  
4. Estimation of time-varying habitat selection, with conditional logistic regression and changepoint analysis: **tvRSF**  
5. Detection of extra-home range excursions and analysis of excursion durations: **Excursions**  



### What's not included in this respository:

1. Linear regressions are generally not included in this repository; these statistical models are common, and our code is not unique or novel for these analyses.
2. Fitting continuous time movement models (CTMM), with calculation of weekly and monthly range areas and centroids. Code for this is thoroughly documented in the literature, and we point interested users to [Silva et al 2021, *Methods in Ecology and Evolution*](https://doi.org/10.1111/2041-210X.13786)

*At the time of publication, movement data were not available from the Wisconsin Department of Natural Resources; restrictions apply to the availability of these data, which were used under a data sharing agreement for the current study, and so are not publicly available. Data may be requested from the Wisconsin Department of Natural Resources through Daniel Storm (DanielJ.Storm@wisconsin.gov).  

White-tailed deer genotype data for prion protein gene *PRNP* codon 96 will be available through ScienceBase upon manuscript acceptance.
