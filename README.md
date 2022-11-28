[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9066812&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-group-assigment-group_17/main)

# 27410 - Group assignment - Group 17 - Production of p-coumaric acid using Synechocystis sp. PCC 6803

## Project summary
The secondary metabolite p-coumaric acid originates from the shikimate pathway from either phenylalanine or tyrosine precursors. It is an important intermediate in the biosynthesis of phenolic acids, flavonoids, and lignin. Also known for its antioxidant, anti-inflammatory, and antimicrobial biological properties, it is a common precursor in the synthesis of flavors and fragrences. Due to these commercial applications, new biological production methods are needed to ensure its sustainable production. This project implements the heterologous phenylalanine pathway for p-coumaric acid in Synechocystis sp. PCC 6803, a mixotrophic cyanobacteria capable of carbon dioxide fixation and fast growth. A product rate of 4.18e-4 mmol/gDW/h was computed. Growth was optimized on a minimal medium and up-regulation target were computationally identified, leading to an X% productivity improvement. Other computer-aided methods for alternative pathway predictions and gene knock-outs failed to yield fruitful improvements. Lastly rational genetic engineering strategies were manually implemented but failed to lead to improvements. Pitfalls of these methods and potential alternatives are discussed.

## Project overview
The complete project report is found in Report.ipynb. Computational work is separated into two files, 3_Selection-and-assessment-of-GSM and 4_cell-factory-engineering.ipynb, corresponding to their respective sections in the report.

Supporting files are listed below:

>Synechocystis_sp_PCC_6803.xml - model generated by reconstruction from reference sequence via CarveMe
>Synechocystis_sp_PCC_6803.html - Memote report for Synechocystis_sp_PCC_6803.xml
>iJN678.xml - model published by King 2016
>iJN678.html - Memote report for iJN678.xml
>iSynCJ816.xml - model published by Joshi 2017
>iSynCJ816.html - Memote report for iSynCJ816.xml
>iSynCJ816_PCOU.xml - model with p-coumaric acid heterologous pathways introduced into Joshi 2017, optimized for p-coumaric acid
>iSynCJ816_PCOU_BG11.xml - model with p-coumaric acid heterologous pathways and BG-11 medium introduced into Joshi 2017, optimized for p-coumaric acid
>iSynCJ816_PCOU_BG11.html - Memote report for iSynCJ816_PCOU_BG11.xml
>requirements.txt - complete list of packages generated via 'pip freeze', not all packages may be relevant

