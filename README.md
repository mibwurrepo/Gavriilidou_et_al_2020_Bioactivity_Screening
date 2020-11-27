Study Title: Bioactivity Screening and Gene-Trait Matching Across Marine Sponge-Associated Bacteria
-------------------------------------------------------------------------------------------------------
Authors: Asimenia Gavriilidou<sup>1</sup>, Thomas Andrew Mackenzie<sup>2</sup>, Pilar Sánchez<sup>2</sup>, José R. Tormo<sup>2</sup>, Colin Ingham<sup>3</sup>, Hauke Smidt<sup>1</sup> and Detmer Sipkema<sup>1</sup>

<sup>1</sup>Laboratory of Microbiology, Wageningen University and Research, 6708 PB Wageningen, The Netherlands<br />
<sup>2</sup>Fundación MEDINA, Centro de Excelencia en Investigación de Medicamentos Innovadores en Andalucía, Avda. del Conocimiento 34, 18016 Granada, Spain<br />
<sup>3</sup>Hoekmine BV, Utrecht, The Netherlands<br />

Correspondence: asimenia.gavriilidou@wur.nl     


This repository contains codes for analysis performed in the research article by Gavriilidou A., et al (2021). "Bioactivity Screening and Gene-Trait Matching Across Marine Sponge-Associated Bacteria." *Marine Drugs*. [submitted]()

Project folder structure:

 ```
 Gavriilidou_et_al_Bioactivity_Screening/
|------- Bioactivity_Screening_assays # contains results from the anticancer activity screening test
           |------ MTT_assay_results.xlsx # cell viability measurements
           |------ README.md # 
|------- data_visualization # contains files used in data analysis with R
           |------ BGCs_heatmap_df.csv # BGC abundance table used in Figure 4
           |------ Cytotoxicity_and_BGCs.Rmd # Codes for generating Figure 3 and 4
           |------ README.md # 
           |------ Screening_MS.Rproj # The Rproject file
           |------ toxicity_barplot_df.csv # Toxicity data used in Figure 3
|------- genomic_analysis # short description.  
           |------ BGC_Abundance.xlsx  # Summary of the BGC abundance (absolute & relative) in the analyzed genomes
           |------ Genomic_Analysis.html # Codes for genome assembly and phylogenetic analysis
           |------ ML_tree_09092020.tree  # Final tree file used in iTOL
           |------ README.md # 
           |------ gtdbtk.bac120.user_msa.fasta # Multiple sequence alignment file used for generating the tree
           |------ reference_genomes_list.txt # List of feference genomes included in the tree
|------- README.md # short description.  
          
```
Instructions:

1. Download the repo and unzip.  
2. Open `Screening_MS.Rproj` in RStudio.  
3. Open `Cytotoxicity_and_BGCs.Rmd` and click knit to reproduce the analysis.   

The figures in the article were further edited to their final format in Inkscape v0.92.3.

For any queries and additional information regarding the analysis described here, contact asimenia.gavriilidou@wur.nl  



