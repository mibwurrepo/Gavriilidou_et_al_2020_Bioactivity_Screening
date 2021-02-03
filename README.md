Study Title: Bioactivity Screening and Gene-Trait Matching Across Marine Sponge-Associated Bacteria
-------------------------------------------------------------------------------------------------------
Authors: Asimenia Gavriilidou<sup>1</sup>, Thomas Andrew Mackenzie<sup>2</sup>, Pilar Sánchez<sup>2</sup>, José R. Tormo<sup>2</sup>, Colin Ingham<sup>3</sup>, Hauke Smidt<sup>1</sup> and Detmer Sipkema<sup>1</sup>

<sup>1</sup>Laboratory of Microbiology, Wageningen University and Research, 6708 PB Wageningen, The Netherlands<br />
<sup>2</sup>Fundación MEDINA, Centro de Excelencia en Investigación de Medicamentos Innovadores en Andalucía, Avda. del Conocimiento 34, 18016 Granada, Spain<br />
<sup>3</sup>Hoekmine BV, Utrecht, The Netherlands<br />

Correspondence: asimenia.gavriilidou@wur.nl     


This repository contains codes for analysis performed in the research article by Gavriilidou A, Mackenzie TA, Sánchez P, Tormo JR, Ingham C, Smidt H, Sipkema D. Bioactivity Screening and Gene-Trait Matching across Marine Sponge-Associated Bacteria. Marine Drugs. 2021; 19(2):75. https://doi.org/10.3390/md19020075

Project folder structure:

 ```
 Gavriilidou_et_al_Bioactivity_Screening/
|------- Bioactivity_Screening_assays # contains results from the anticancer activity screening test
           |------ MTT_assay_results.xlsx # cell viability measurements
           |------ README.md # information on contents of directory
|------- data_visualization # contains files used in data analysis with R
           |------ BGCs_heatmap_df.csv # BGC abundance table used in Figure 4
           |------ Cytotoxicity_and_BGCs.Rmd # Codes for generating Figure 3 and 4
           |------ README.md # information on contents of directory
           |------ Screening_MS.Rproj # The Rproject file
           |------ toxicity_barplot_df.csv # Toxicity data used in Figure 3
|------- genomic_analysis # short description.  
           |------ BGC_Abundance.xlsx  # Summary of BGC abundance in the genomes
           |------ Genomic_Analysis.html # Codes for genome assembly and phylogenetic analysis
           |------ ML_tree_09092020.tree  # Final tree file used in iTOL
           |------ README.md # information on contents of directory
           |------ gtdbtk.bac120.user_msa.fasta # Multiple sequence alignment file used for generating the tree
           |------ reference_genomes_list.txt # List of reference genomes included in the tree
|------- README.md # study information and project folder structure
          
```

For any queries and additional information regarding the analysis described here, contact asimenia.gavriilidou@wur.nl  



