# Vision-Predictive-Modeling

## Background

Age-related macular degeneration (AMD) is the leading cause of irreversible vision loss in the elderly in developed countries. Choroidal neovascularization (CNV) is a hallmark for the exudative or “wet” form of the disease and is induced by vascular endothelial growth factor (VEGF). To date, there are no known cures for AMD. However, treatment for the disease is anti-VEGF therapy, which involves monthly intravitreal injections of antiangiogenic drugs, which are costly, invasive, and a clinical burden. Therefore, it is important to determine and monitor how vision will improve with anti-VEGF therapy to personalize treatment.

Prior studies have shown that characterization of retinal structures is correlated with treatment response. In a study by Fu et al, optical coherence tomography (OCT) images were captured from AMD patients and biomarker volumes were quantified through a deep-learning segmentation algorithm. In their analysis, they sought to identify the predictive power of these OCT biomarkers for visual acuity at future timepoints. In their regression model, their covariates are OCT biomarkers, measured in volume as mm3, and baseline visual acuity (determined by an ETDRS exam). Their response is visual acuity at a given time point. 


## Project Summary

In our project we hope to expand on their regression model by incorporating categorical independent variables such as gender and ethnicity, as these are known risk factors for AMD. This project is divided into two parts. In the first part, we incorporate linear OLS regression to achieve the following goals: 1) to determine whether these OCT biomarkers are associated with visual acuity, and 2) to predict visual acuity one year after the start of anti-VEGF therapy given the results from the first two months.

In the second part of this project, we have the goal of determining whether a parametric or non-parametric approach would be favorable in predicting patient vision class using the biomarker data. We do this by attempting a multinomial regression to classify the patients, and comparing the results with performing k-nearest neighbors (kNN) classification. For more information, please reach out to Ethan Mai: 1mai.ethan@gmail.com
