## Minimum information when reporting the metabolomics/ shotgun proteomics QC experiment


## General Features - Global descriptors
- Contact information (responsible person or role)

  provide name, affiliation and stable contact information
- Experiment identifier or name

## General Features - Material 

- Chromatographic materials
  - Analytical chromatography columns: This is specific to chromatographic method, e.g., C18, C8, HILIC, HSS.
- Chromatographic instrumentation
  - Chromatography instrument
  - Mass spectrometer
  - Ion source
  - Ionization mode
- Software: Provide software name, version and manufacturer. The software Include data acquisition and processing software, peak picking software, etc.



## Methods - Experimental design

A short introduction of the experiment. Provide the information as follows.
- Experimental protocol (if applicable, provide URL/Citation)

**Or** provide a short description of the experimental protocol including the following information.

  - Organism
  - Sample Description
  - Tissue/Cell Type
  - Groups; Provide the description of the experimental sample grouping including group names.


## Methods - Experimental Preparation

- Analytical System Preparation
  - Condition of Mass Spectrometer: Provide information about what users have done to achieve maximum mass accuracy and resolution before starting the experiment.
  - QC Replicates
- Sample Handling & Preparation
  - Provide information about what users have done to avoid unnecessary freeze/thaw cycles.
  - Provide information about what users have done to avoid the freezer malfunction takes place.
  - Provide information about what users have done to to avoid carbamylation artifacts in protein denaturation.
- Analytical Sequence Preparation
  - Order of the Samples: A short description of the sample order. Make sure the the order of the samples is randomized. 
  
  This is to avoid introducing bias due to changes between run "batch" effects.
  - Order of QC Samples: A short description of the QC sample order. 
  
  Make sure the order of QC samples is not randomized. It should be inserted regularly in the run sequence.
  - Number of QC Samples
  - Way to improve quantification aspects

## Data Analysis - Data Processing

- Acceptance criteria
  - m/z region
  - Retention time
  - Peak area
  - Scan time 
- Optimum parameters: Provide the optimum parameters for the software used for peak alignment, peak peaking and integration.

## Data Analysis - Quality Evaluation 

- Retention time variation

Provide a list/table that contains the retention times of analytes that be detected and monitored.
- Dwell time variation

Provide a list/table that contains the dwell times of analytes that be detected and monitored.



## To meet the above information, one can provide a short description like this:

This study presented a **personal [Organism]** metabolomics profile from **a single individual over a 9-month period [Sample Description]**. About 120 L of the **serum sample [Tissue/Cell Type]** was used for this study. **All samples were divided into into appropriate number of sub-aliquots and ordered for the latter storage [What users have done to avoid unnecessary freeze/thaw cycles.]**. What’s more, **the sub-aliquots were stored in different freezers [What users have done to avoid the freezer malfunction takes place]**. **Proteins were precipitated by incubating the samples at -20°C for 1 h. Samples were then centrifuged at 10,000 rpm at 4°C for 10 min. The supernatant was collected and dried for metabolomics analysis. The urea solution had been prepared during the week before denaturation took place [Sample handling and preparation]**. Chromatographic analysis was performed on a **HSS T3 C18 column [Analytical chromatography columns]**. And an **ultrahigh performance liquid chromatography (U(H)PLC) system [Chromatography instrument]** coupled to a high-resolution mass spectrometer by **SCIEX [Mass spectrometer]** with an **ESI source [Ion Source]** was adopted for the identification of metabolite. The analysis was performed in **positive (ESI+) mode [Ionization mode]**. **Waters MassLYnx 4.10.0 [Software]** was adopted for data acquisition and processing, and **SCIEX MarkerView 1.3.1 [Software]** was used for peak picking. **Before starting, the mass spectrometer had been calibrated following the appropriate procedure recommended by the vender [Information about what users have done to achieve maximum mass accuracy and resolution]**. Data were recorded for the **m/z region of 50–1000 in V-mode [m/z region]** with **a scan time of 0.20s [Scan time]** and dwell time of 0.01s between scans. The collision energy for each analyte after direct infusion and optimum time window and dwell times are presented in **Table 1 [Retention time variation & Dwell Time variation]**. The samples were analyzed in **random order [Sample Analysis Order]** and QC samples were analyzed **every 5 samples [QC Sample Analysis Order]**. For the chromatography alignment, only ions with intensity above **5,000 counts [Ion Intensity]** and **retention time window within 0.2 min [Retention Time]** were selected. 


## Table 1


|Metabolites|Formula|Monoisotopic mass|Precursor ion|Product ion|RT(min)|Molecular weight|Dwell time|
|-------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|2-Hydroxyisovaleric acid|C5H10O3|118.06|117|71|6.0|118.13|0.005|
|2-MethylHippuric acid|C10H11NO3|193.20|192|148|8.2|193.20|0.005|
|3-Methylhistidine|C7H11N3O2|169.09|170|109|19.0|169.17|0.003|






 
