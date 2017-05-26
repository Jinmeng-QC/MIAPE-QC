# **MIAPE-QC**

Jinemng Jia, Martin Eisenacher, Mathias Walzer, Wout Bittremieux, Reza M. Salek, Stefan Tenzer, Weimin Zhu and David L. Tabb 

## **Abstract** 
*Quality control (QC)* is increasingly recognized as a crucial aspect of mass spectrometry based proteomics. As a result, software tools for computing quality control metrics for mass spectrometry data started to proliferate in recent years. However, as the different tools that compute the diverse metrics from experimental LC-MS/MS data can extract only a limited number of QC features, it is a challenging task to compare and integratively analyze the outputs of these tools. In addition, the data reproted by differnent individuals is often missing key pieces essential for a full understanding of the experiment and the possibility of meta-analysis. Here, we propose MIAPE-QC, the Minimal Information. Adherence to this reporting guideline will result in increased clarity of publications and suopport the effectivenss and accuracy of investigations based on the experimental proteomics data.


---


## **General Fetures**

#### ***Global descriptors***
- Contact information:

  The (stable) primary contact person for this data set; this could be the experimenter, lab head, line manager, etc. Where responsibility rests with an institutional role (e.g. one of a number of duty officers) rather than a person, give the official name of the role rather than any one person. In all cases give affiliation and stable contact information.
  
  **CV term:** MS:1000585 / contact attribute 

  **Synonym:** responsible person or role
  
  **Reason:**  In case of concern or discussion about the file.
- Instrument manufacturer, model:

  The manufacturing company and model name for mass spectrometer.
  
  **CV term:** MS:1000031 / instrument model 

  **Synonym:** instrument model
  
  **Reason:**  
  
- Mass spectrometer customization:

  Free text description of a single customization made to the instrument; for several modifications, use several entries.
  
  **CV term:** MS:1000032 / customization 

  **Synonym:** mass spectrometer summary
  
  **Reason:**  Provide any significant deviations from the manufacturer’s specification for the mass spectrometer.
  
- Quantitation software comment or customization:

  Quantitation software comment or any customizations to the default setup of the software.
  
  **CV term:** MS:1001832 / quantitation software comment or customizations  

  **Synonym:** quantitation software summary
  
  **Reason:**  Provide any significant deviations from the manufacturer’s specification for the quantitation software.
- Quality control generating software customization:

  Quality control tool's name, version and any customizations to the default setup of the software.
  
  **CV term:**   

  **Synonym:** 
  
  **Reason:**  Provide any significant deviations from the version's or manufacturer's specification for the QC generating software.
- Availability of the software:

  The references of the vendor or public url if a publicly available version has been used.
  
  **CV term:**  

  **Synonym:** 
  
  **Reason:** 

#### ***Experimental design and sample description***
- Number of QC runs

  Provide how many QC runs are included in the experiment.
  
  **CV term:**  

  **Synonym:** 
  
  **Reason:** Essential information should be included in experimental design.
- QC sample: 

  Terms to describe the QC sample.
  
  **CV term:** 

  **Synonym:** source
  
  **Reason:**  
- Input file format: 

  The format of the file being used. This could be a instrument or vendor specific proprietary file format or a converted open file format.
  
  **CV term:** MS:1000560 /  mass spectrometer file format 

  **Synonym:** location of source and processed files
  
  **Reason:** 

  
## MS acquisition parameters

#### ***Chromatography***
- Chromatogram count: 

  The format of the file being used. This could be a instrument or vendor specific proprietary file format or a converted open file format.
  
  **CV term:** MS:1000560 / customization 

  **Synonym:** location of source and processed files
  
  **Reason:** 
- Retention time (ranges): 

  A time interval from the start of chromatography when an analyte exits a chromatographic column. This shouled contains the min/max RT range boundaries observed during MS acquisition.
  
  **CV term:** MS:1000894 / retention time; QC:0000012 / MS RT acquisition ranges 

  **Synonym:** RT, RT ranges
  
  **Reason:** 

#### ***Ion source***
- MZ (ranges): 

  The format of the file being used. This could be a instrument or vendor specific proprietary file format or a converted open file format.
  
  **CV term:** QC:0000009 / MS MZ acquisition ranges 

  **Synonym:** MS MZ acquisition ranges
  
  **Reason:** 

#### ***MS1 signal***
- Ion injection time: 

  Full MS scan ion injection time which contains the accumulation time in the ion trap device used in machine settings during MS acquisition.
  
  **CV term:** QC:0000017 / MS1 injection time 

  **Synonym:** MS1 injection time; full MS scan ion injection time
  
  **Reason:** 
- MS1 scan time: 

  Average scan time for Full MS scan used in machine settings.
  
  **CV term:** QC:0000019 / MS1 scan time 

  **Synonym:** MS1 scan time; full MS scan time
  
  **Reason:** : 
- XIC value: 

  Summed area of all the extracted ion chromatogram for the peptide (e.g. of all the transitions in SRM).
  
  **CV term:** MS:1002412 / Total XIC area 

  **Synonym:** XIC
  
  **Reason:** : 
- MS1 intensity variation for peptides: 

  Average of between series intensity variations for identified peptides and the ratio of average intensity variation between series to average intensity variation within a series.
  
  **CV term:**  

  **Synonym:** 
  
  **Reason:** : 
- Precursors: 

  Provide table of measured precursor ions over retention time/mz.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** : 
- Delta ppm: 

  Provide the deviation/mean deviation/median deviation of the precursor ion mass(es) from the theoretical mass(es) of the matched identification(s).
  
  **CV term:** QC:0000039 / Delta ppm

  **Synonym:** 
  
  **Reason:** : 
- MS1 scan spectra count: 

  Number of full MS scan spectra.
  
  **CV term:** QC:0000006 / MS1 spectra count 

  **Synonym:** full MS scan spectra count
  
  **Reason:** : 

#### ***Dynamic sampling***
- MS1 scans: 

  Number of full MS scans taken over time period over which 50% of peptides were identified.
  
  **CV term:** 

  **Synonym:** full MS scans
  
  **Reason:** To evaluate the experiment. Fewer MS1 scans indicates more sampling.
- MS2 scans: 

  Number of tandem MS scans taken over time period over which 50% of peptides were identified.
  
  **CV term:** 

  **Synonym:** MS/MS scans; tandem MS scans
  
  **Reason:** To evaluate the experiment. More MS2 scans indicates more sampling.
  
#### ***MS2 scan signal***
- MS2 spectra count: 

  Number of tandem MS scan spectra.
  
  **CV term:** QC:0000007 / MS2 spectra count

  **Synonym:** Tandem MS spectra count
  
  **Reason:** 
- MS2 scan time: 

  Average scan time for Tandem MS event used in machine settings.
  
  **CV term:** QC:0000012 / MS2 scan time

  **Synonym:** tandem MS scan time
  
  **Reason:** 
- MS2 injection time: 

  Contains the accumulation time in the ion trap device used in machine settings during MS acquisition.
  
  **CV term:** QC: 0000018 /MS2 injection time

  **Synonym:** tandem MS injection time 
  
  **Reason:** 
- MS2 identification peaks: 

  Provide the number and median number of peaks in an Tandem MS scan
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** 
  
## MS identification parameters

#### ***Spectrum identification***
- Estimated spectra FDR: 

  Provide the false discovery rate of the estimated spectra.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** 
- ID spectra ratio: 

  The number of identified spectra vs. The number of total spectra.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** 
- Precursor error: 

  Provide the maximum and median number of precursor error.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** 

#### ***Peptide identification***
- Estimated peptide FDR: 

  Provide the false discovery rate of the estimated peptide.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** 
- ID peptide ratio: 

  The number of identified peptides vs. The number of recorded Tandem MS spectrum.
  
  **CV term:** 

  **Synonym:** 
 
  **Reason:** 
- Average spectra count per peptide: 

  Average number of spectra matched to one peptide.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** 
- Average peptide ion count per peptide: 

  **CV term:** 

  **Synonym:** 
  
  **Reason:** 
- Missed cleavages: 

  Provide the maximum and median number of precursor error.
  
  **CV term:** QC:0000037 / total number of missed cleavages

  **Synonym:** 
  
  **Reason:** :
- Peptide counts: 

  This number indicates the number peptides that were identified.Provide ratio of semi/fully tryptic peptide IDs, ratio of non-tryptic peptide IDs as well as ratio of missed-cleavage peptide IDs.
  
  **CV term:** == / total number of identified== peptides

  **Synonym:** 
  
  **Reason:** :
- Ions: 

  Provide the number of tryptic peptide identified.
  
  **CV term:** 

  **Synonym:** 
  
  **Reason:** :
- TIC: 

  The percentage of tic slumps below 10k.
  
  **CV term:** QC:0000023 / TIC slump

  **Synonym:** TIC slump
  
  **Reason:** :
- Total number of PSMs: 

  This number indicates the number of spectra that were given peptide annotations.
  
  **CV term:** QC:0000029 / total number of PSMs

  **Synonym:** 
  
  **Reason:** :

#### ***Protein identification***
- Protein count: 

  Total number of identified proteins.
  
  **CV term:** QC:0000032 /  total number of identified proteins

  **Synonym:**  total number of identified proteins
  
  **Reason:** :
- Uniquely protein count: 

  Total number of uniquely identified proteins.
  
  **CV term:** QC: 0000033 / total number of uniquely identified proteins

  **Synonym:** total number of uniquely identified proteins
  
  **Reason:** :
- Modified peptides count: 

  This number indicates the number modified peptide sequences that were identified (after FDR).
  
  **CV term:** QC:0000029 / total number of modified peptides

  **Synonym:** total number of modified peptides
  
  **Reason:** :
- Protein coverage 

  Provide median and average protein coverage. Meanwhile, provide protein coverage for each protein.
  
  **CV term:**

  **Synonym:** 
  
  **Reason:** :
- Estimated protein FDR 

  Provide the false discovery rate of the estimated protein.
  
  **CV term:**

  **Synonym:** 
  
  **Reason:** :
  
#### ***Protein group and inference***
- Protein count for parsimony protein group 

  Provide the average and median protein count for parsimony protein group.
  
  **CV term:**

  **Synonym:** 
  
  **Reason:** :
- Missed protein group 

  Missed protein group in the parsimony protein list.
  
  **CV term:**

  **Synonym:** 
  
  **Reason:** :
- Protein group ratio

  Provide ratio of unique protein group to parsimony protein group
  
  **CV term:**

  **Synonym:** 
  
  **Reason:** :

## **MS quantification methods and parameters**

#### ***Quantification methods***
- Protocol of label-based quantification methods (if applicable)

  In the case of label-based quantification methods, provide the name and protocol of it, including the labelling level.  
  
  **CV term:**

  **Synonym:** 
  
  **Reason:** :

#### ***Quantification parameters***
- Number of features

  The number of features reported.
  
  **CV term:** QC:0000046 / Number of features

  **Synonym:** 
  
  **Reason:** :
  
  

### ***Appendix One.*** 
The MIAPE: QC glossary of required-parameter classifications

Classification | Definition | Details |
:---|:---|:---|
Contact information | Details about a person or organization to contact in case of concern or discussion about the file. | The (stable) primary contact person for this data set; this could be the experimenter, lab head, line manager, etc. Where responsibility rests with an institutional role (e.g. one of a number of duty officers) rather than a person, give the official name of the role rather than any one person. In all cases give affiliation and stable contact information.
Instrument manufacturer, model | The manufacturing company and model name for mass spectrometer. | Instrument model name not including the vendor’s name.
Mass spectrometer customization | Free text description of a single customization made to the instrument; for several modifications, use several entries. | Any significant deviations from the manufacturer’s specification for the mass spectrometer.
Quantitation software comment or customization | Quantitation software comment or any customizations to the default setup of the software. | Any significant deviations from the version's or manufacturer’s specification for the quantitation software.
Quality control generating software customization | Quality control tool's name, version and any customizations to the default setup of the software. | Provide any significant deviations from the version's or manufacturer's specification for the QC generating software.
Availability of the software | The references of the vendor or public url if a publicly available version has been used. | 
Number of QC runs| | Provide how many QC runs are included in the experiment.
QC sample | Terms to describe the sample. | A description of the source, such as means of collection, volume, concentration or previous step of processing.
Input file format | The location of the data generated. Ideally this should be an URI + filename. | The format of the file being used. This could be a instrument or vendor specific proprietary file format or a converted open file format.
Chromatogram count | | Contains the number of chromatograms recorded.
Retention time (ranges) | A time interval from the start of chromatography when an analyte exits a chromatographic column. | peptide identification during time period over which 50% of peptides were identified.
MZ (ranges) |  | Provide median MZ for all identified peptides, min/max MZ range boundaries observed, minimum MZ detected and maximum MZ detected.
Ion injection time | Full MS scan ion injection time. | Contains the accumulation time in the ion trap device used in machine settings during MS acquisition.
MS1 scan time | Average scan time for Full MS scan used in machine settings. | 
XIC value | Summed area of all the extracted ion chromatogram for the peptide (e.g. of all the transitions in SRM). | Provide the median XIC value for identified peptides over same time period as used for median signal-to-noise value. 
MS1 intensity variation for peptides | Average of between series intensity variations for identified peptides and the ratio of average intensity variation between series to average intensity variation within a series. | 
Precursors |  | Provide table of measured precursor ions over retention time/mz.
Delta ppm |  | Provide the deviation/mean deviation/median deviation of the precursor ion mass(es) from the theoretical mass(es) of the matched identification(s).
MS1 scan spectra count | Number of full MS scan spectra. | Contains the number of MS1 spectra recorded.
MS1 scans | Number of full MS scans taken over time period over which 50% of peptides were identified. | 
MS2 scans | number of tandem MS scans taken over time period over which 50% of peptides were identified. | 
MS2 spectra count | Number of tandem MS scan spectra. | Contains the number of MS2 spectra recorded.
MS2 scan time | Average scan time for Tandem MS event used in machine settings. | Contains the	average scan time for a MS2 event used in machine settings during MS acquisition. 
MS2 injection time | Tandem MS ion injection time. | Contains the accumulation time in the ion trap device used in machine settings during MS acquisition. 
MS2 identification peaks |  | Provide the number and median number of peaks in an Tandem MS scan.
Estimated spectra FDR |  |Provide the false discovery rate of the estimated spectra.
ID spectra ratio | The number of identified spectra vs. The number of total spectra. | 
Precursor error |  | Provide the maximum and median number of precursor error.
Estimated peptide FDR |  | Provide the false discovery rate of the estimated peptide.
ID peptide ratio | The number of identified peptides vs. The number of recorded Tandem MS spectrum. | 
Average spectra count per peptide | Average number of spectra matched to one peptide. | 
Average peptide ion count per peptide | Average peptide ion count per peptide. | 
Missed cleavages | This number indicates the number missed cleavages that were identified. | Provide the total number of missed cleavages.
Peptide counts | This number indicates the number peptides that were identified. | Provide ratio of semi/fully tryptic peptide IDs, ratio of non-tryptic peptide IDs as well as ratio of missed-cleavage peptide IDs.
Ions |  | Provide the number of tryptic peptide identified.
TIC | The percentage of tic slumps below 10k. | Provide table of total ion currents detected in each of a series of mass spectrum and the number of tic slumps below 10K.
Total number of PSMs | This number indicates the number of spectra that were given peptide annotations. | 
Protein count | This number indicates the number proteins that were identified. | Provide the total number of identified proteins.
Uniquely protein count | This number indicates the number proteins that were uniquely identified. | Provide the total number of uniquely identified proteins.
Modified peptides count | This number indicates the number modified peptide sequences that were identified (after FDR). | Provide the number of spectra that were given peptide annotations.
Protein coverage |  | Provide median and average protein coverage. Meanwhile, provide protein coverage for each protein.
Estimated protein FDR |  | Provide the false discovery rate of the estimated protein.
Protein count for parsimony protein group |  | Provide the average and median protein count for parsimony protein group.
Missed protein group |  | Provide missed protein group in the parsimony protein list.
Protein group ratio |  | Provide ratio of unique protein group to parsimony protein group
Protocol of label-based quantification methods (if applicable) |  | In the case of label-based quantification methods, provide the name and protocol of it, including the labelling level.
Number of features | The number of features reported. | 
