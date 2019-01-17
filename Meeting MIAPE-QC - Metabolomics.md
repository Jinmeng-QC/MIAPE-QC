**Minimum checklist for the metabolomics QC experiment** 

# Targeted Metabolomics

## Material 

- Chromatographic Materials & Instrumentation
  - Instrumentation
  - Software
  
  Softwares include but are not limited to the following:
  Data acquisition and processing software (e.g., Excalibur, MassLYnx, Analyst, or other). Special software for peak picking such as Marker Lynx, Sieve, MarkerView (or other vendor software), or open-source/free software (XCMS, MzMine, MetAlign or other). Microsoft Excel, Statistica, and other advanced spreadsheet software. SIMCA-P or other software for multivariate statistical analysis.
  - Ion Source
  - Ionization Mode
  
To meet the above information, one can provide a short description like this: Chromatographic analysis has been performed on a HSS T3 C18 column. And an **ultrahigh performance liquid chromatography (U(H)PLC) system [Instrumentation]** coupled to a **high-resolution mass spectrometer [Software]** with an **ESI source [Ion Source]** has been adopted. The analysis was performed **in positive (ESI+) mode [Ionization Mode]**.


## Methods - Experimental design

A short introduction of the experiment. Provide the information as follows. 
- Organism
- Sample Description
- Tissue/Cell Type
- m/z Region
- Scan Time
- Dwell Time: Provide a list/table that contains the dwell times of analytes that be detected and monitored.

To meet the above information, one can provide a short description like this: This study presented a **Personal [Organism]** metabolomics profile from **a single individual over a 10-month period [Sample Description]**. About 120 uL of **the serum sample [Tissue/Cell Type]** was used for this study. Data were recorded for the **m/z region of 50–1000 in V-mode [m/z Region]** with **a scan time of 0.20s [Scan Time]** and dwell time of 0.01s between scans. The collision energy for each analyte after direct infusion and optimum time window and dwell times are presented in **Table 1**.

Table 1

|ID|Matabolites|Formula|Monoisotopic mass|Precursor ion|Product ion|RT(min)|Molecular weight|Dwell time|
|---|---------|-------|------|------|------|------|------|------|
|1|2-Hydroxyisovaleric acid|C<sub>5</sub>H<sub>10</sub>O<sub>3</sub>|118.06|117|71|6.0|118.13|0.005|
|2|2-MethylHippuric acid|C<sub>10</sub>H<sub>11</sub>NO<sub>3</sub>|193.20|192|148|8.2|193.20|0.005|
|3|3-Methylhistidine|C<sub>7</sub>H<sub>11</sub>N<sub>3</sub>O<sub>2</sub>|169.09|170|109|19.0|169.17|0.003|

## Methods - Experimental Preparation

- Analytical System Preparation
  - Condition of Mass Spectrometer --> _Make sure the mass spectrometer is in a suitable condition for the analysis of samples. Provide information about what users have done to achieve maximum mass accuracy and resolution before starting the experiment._
  - QC Replicates --> _Run a suitable number of QC samples to achieve system stability._
- Sample Handling & Preparation
  - Number of Sub-aliquots --> _Provide information about what users have done to avoid unnecessary freeze/thaw cycles._
  - Storage of Sub-aliquots --> _Provide information about what users have done to avoid the freezer malfunction takes place._
- Analytical Sequence Preparation
  - Order of the Samples --> _Make sure the the order of the samples is randomized. This is to avoid introducing bias due to changes between run "batch" effects._ 
  - Order of QC Samples --> _Make sure the order of QC samples is not randomized. It should be inserted regularly in the run sequence._ 
  - Number of QC Samples 
  - Solution Injections --> _Standard solution injections should be avoided within the batch of test samples, as the system can be disequilibrated by the injection of non-matrix solutions._
  - Blank Sample Injections --> _Blank sample injections should be avoided._
  - Way to improve quantification aspects

- _**For Untargeted Metabolomics **_
  - In untargeted metabolomic studies, data analysis strategies require some steps involving raw data acquisition, normalization, scaling and feature and peak detection in order to finally reach biomarker detection and identification. 



## Data Processing & Quality Evaluation

From the raw data acquired, observe the following metrics from indicative chromatographic peaks located at the **beginning, middle and end of the chromatogram**.

- Peak Width
- Retention Time
- Peak Intensity
- Mass accuracy
- Noise Intensity 


## 

This study presented a **Personal [Organism]** metabolomics profile from **a single individual over a 10-month period [Sample Description]**. About 120 uL of **the serum sample [Tissue/Cell Type]** was used for this study. **Metabolites were extracted by adding four times volume of equal-volume mixture of methanol, acetonitrile, and acetone that were pre-chilled at -20°C. Proteins were precipitated by incubating the samples at -20°C for 1 h. Samples were then centrifuged at 10,000 rpm at 4°C for 10 min. The supernatant was collected and dried for metabolomics analysis [Sample Preparation Description]**. The identification of metabolites from the extracted samples were using **Agilent 1260 LC system and Agilent 6538 Q-TOF MS spectrometer [Instrument Description]** equipped with **electrospray ionization [Ion Source]**. The analysis was performed **in positive (ESI+) mode [ionization mode]**. Data were recorded for the **m/z region of 50–1000 in V-mode [m/z Region]** with **a scan time of 0.20s [Scan Time]** and **dwell time of 0.01s [Dwell Time]** between scans. The samples were analyzed **in random order [Sample Analysis Order]** and **QC samples were analyzed every 5 samples[QC Sample Analysis Order]**. For the chromatography alignment, only ions **with intensity above 5,000 counts [Ion Intensity]** and **retention time window within 0.2 min [Retention Time]** were selected.  

# Untargeted Metabolomics

## Material 
- Analytical columns: specific to chromatographic method, e.g., C18, C8, HILIC, HSS.

To meet the above information, one can provide a short description like this: Chromatographic analysis has been performed on a **HSS T3 C18 column[Analytical columns]**.
