Study Title: Bioactivity Screening and Gene-Trait Matching Across Marine Sponge-Associated Bacteria
Authors: Asimenia Gavriilidou1, Thomas Andrew Mackenzie2, Pilar Sánchez2, José R. Tormo2, Colin Ingham3, Hauke Smidt1 and Detmer Sipkema1

1Laboratory of Microbiology, Wageningen University and Research, 6708 PB Wageningen, The Netherlands
2Fundación MEDINA, Centro de Excelencia en Investigación de Medicamentos Innovadores en Andalucía, Avda. del Conocimiento 34, 18016 Granada, Spain
3Hoekmine BV, Utrecht, The Netherlands

Correspondence: asimenia.gavriilidou@wur.nl

This repository contains codes for analysis performed in the research article by Gavriilidou A., et al (2021). "Bioactivity Screening and Gene-Trait Matching Across Marine Sponge-Associated Bacteria." Marine Drugs. submitted
Project folder structure:

``
Gavriilidou_et_al_Bioactivity_Screening/
|------- Quality_Control_&_Genome_Assembly/ # short description.
          |------ readme.txt # all genomes used are publicly available there...raw reads are there 
          |------ code.rmd
|------- Phylogenetic_Analysis/ # short description.  
          |------ .msa  # tree in itol
          |------ .tree  # tree in itol
          |------ .svg  # tree in itol
          |------ .txt  # reference genomes(accession numbers)
|------- Genome_mining/ # short description.  
          |------ readme.txt # antiSMASH online
     |------- 
     
|------- Data_visualization/ # contains ............ 
     |------- input_data/ # short description.
          |------  .csv# short description.  
          |------  .csv
     |-------- output_data/ # short description.  
          |------ Figure_2.tif
          |------ Figure_3.tif
     |------- code.rmd # short description.  
           
         
|------- Bioactivity_Screening_Assays #contains .......
     |------- Raw_data/ # short description.
          |------ antimicrobial_activity_test_results.xlsx #describe
          |------ cell_viability_test_results.xlsx #describe
 
 ``

Instructions:

1. Download the repo and unzip.  
2. Open `Screening_MS.Rproj` in RStudio.  
3. Open `Cytotoxicity_and_BGCs.Rmd` and click knit to reproduce the analysis.   

The figures in the article were further edited to their final format in Inkscape v0.92.3.

For any queries and additional information regarding the analysis described here, contact asimenia.gavriilidou@wur.nl
