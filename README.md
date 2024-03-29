# Supervised machine learning is superior to indicator value inference to monitor environmental impact of salmon aquaculture using eDNA metabarcodes

This repository includes all codes used in "Supervised machine learning is superior to indicator value inference to monitor environmental impact of salmon aquaculture using eDNA metabarcodes" by Frühe, Cordier, Dully, Breiner, Pawlowski, Martins, Wilding &amp; Stoeck. 

<div id="badges">
  <a href="https://onlinelibrary.wiley.com/doi/full/10.1111/mec.15434/">
    <img src="https://img.shields.io/badge/MolecularEcology-darkblue?style=for-the-badge&logo=molecularecology&logoColor=white" alt="MolEcol Badge"/>
  </a>
 <div/>
  
  
---


In the file SML_Analysis.R you will find everything you need to run Supervised Machine Learning tests on our dataset. The accompanied file meta.txt is a metadatatable corresponding to the samples we used (see Ssupplementary Information 1 of the paper).  

In the file ASV_inference &amp; IndVal all codes used to infer IndVals for ASVs are deposited, as well as all codes to retrieve ASVs from HTS data and to perform nonmetrical multidimensonal scaling plots and scatterplots.  

Increasing anthropogenic impact and global change effects on natural ecosystems have prompted the development of less expensive and more efficient bioassessments methodologies. One promising approach is the integration of DNA metabarcoding in environmental monitoring, which alleviates some of the limitations of traditional microscopy-based biomonitoring using macroinvertebrates as bioindicators. Environmental DNA metabarcoding also allows the use of microorganisms as bioindicators. One critical step in this process is the inference of ecological quality (EQ) status from identified molecular bioindicator signatures to classify environmental samples in the same way as done in current standard macroinvertebrate-based monitoring. The most promising approaches to infer EQ from biotic indices (BI) are supervised machine learning (SML) and the calculation of indicator values (IndVal). In this study we compared the performance of both approaches using DNA metabarcodes of bacteria and ciliates as bioindicators obtained from 152 samples collected from seven Norwegian salmon farms. Results from traditional macroinvertebrate-monitoring of the same samples were used as reference to compare the accuracy of both approaches. First, SML outperformed the IndVal approach to infer EQ from eDNA metabarcodes. The Random Forest (RF) algorithm appeared to be less sensitive to noisy data (a typical feature of massive environmental sequence data sets) and uneven data coverage across EQ classes (a typical feature of environmental compliance monitoring scheme) compared to a widely used method to infer IndVals for the calculation of a BI. Second, bacteria allowed for a more accurate environmental impact assessment than ciliate eDNA metabarcodes. For the implementation of DNA metabarcoding into routine monitoring programs to assess ecological quality around salmon aquaculture cages, we therefore recommend bacterial DNA metabarcodes as bioindicators and SML to classify EQ categories based on molecular signatures.
