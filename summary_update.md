## Summary

**Overiew**

Information and parameters in MIAPE-QC checklist are mainly extracted from three parts: the metadata fields collected from the public experimental reports, the QC metrics generated from different QC tools and the essential parameters listed in PSI MIAPE-like documents. For each parameter/metric in MIAPE-QC checklist, not only the description (including concise definition and details) but also annotations (e.g. synonyms, related existing CV terms) will be provided to eliminate its ambiguity and inconsistence through different sources. What's more, a short description about the reason why this information should be submitted will also be added to make the readers a better understanding.  

**Statistics**

- Minimal information parameters: 49
- Categories: 

  ***Top categories***: 4 (general fetures, MS aquisition parameters, MS identification parameters, MS quantification parameters)
  
  ***Secondary categories***: 9 (global descriptors, experimental design and sample description, chromatography, ion source, MS1 signal, dynamic sampling, MS2 signal, peptide identification, protein identification )

**Suggestions and changes**

- Martin did a few revise to the first draft of MIAPE-QC, and suggested to consider if we need to add separation between “run metrics” and “set metrics” when classify terms in MIAPE-QC checklist.
- Dave introduced Binz Pirre-Alain for his enrichment experience in drafting MIAPE guidelines. Binz thought MIAPE guideline should be expressed in a popular and easy-to-understand way to make sure the readers can easily accept. 
- Based on the feedback of our poster posted in 2016 HUPO conference, people's interests for CV and MIAPE-QC are mainly around: 
  
  - Develope brand new terms or use ontology reusing method?
  - Consistency between "overlap" terms? Especially obsolete CV terms.
  
    Examle:   
    > QC metrics | Existing CV terms | Obsolete CV terms|
    > ---|---|---|
    > Filename [QuaMeter]: Location of source and processed files  | PSI-MS: mass spectrometer file format [MS:1000560]: The name and location of the file. Ideally this should be an URI + filename. | ~~ProteomeDiscoverer:Spectrum Files:Raw File names [MS:1001601]~~ (replaced by MS:1000560)
  ** *If in this condition, which one should we use as a presentation in qcCV? Or just develop a new one?***
  - Minimal data means "must" data must be provided under method-speci fic conditions? 
  - If the qcCV can be used to extract accurate information (metrics, essencial parameters) from reports from different resources or published papers? 
- The clssification/categorization of MIAPE-QC is still under consideration. (Usually, a MIAPE-like document classifies terms through workflow of the experiment/process, which ususally consists of global descriptors, experimental design, essencial parameters and descriptors through the whole workflow, which usually from the input to the output part.) For MIAPE-QC, classification methods of QC metrics like "set metrics"/"run metrics" and "inter-experiment metrics"/"intra-experiment metrics" should under consideration. 

### Working Progress 

From **April 28th, 2017** (after the disscusion in Beijing) to **May 25th, 2017**.

- [x] - Collected qc metrics and mapping metrics throuh existing CVs. 
- [x] - Extracted minimal metrics for MIAPE-QC (extracted 40 QC metrics from all the metrics collected from QC tools and 9 essential parameters/descriptors from experimental reprots and MIAPE-like documents)
- [x] - Added title, authors and abstract as a start point of MIAPE-QC based on Martin's suggestion. 
- [x] - Added some metrics to the QC Wishing list after talked with experts and experimenters in Beijing (Phenix Center). 
- [x] - Updated the old version of MIAPE-QC list.
- [ ] - Adjust the classification of metrics and parameters in MIAPE-QC.
- [ ] - Complete the definition/details/reasons of all the terms shown in the checklist. 



