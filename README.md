# Data-and-codes-associated-with-Vidal-Cordasco-et.-al-2023
Here data and codes are available to reproduce the models and figure rendering of the paper: “Carrying capacity affected Neanderthal coexistence with modern humans”.  

This research is based on two set of data: 1) herbivore species recovered from archaeo-palontological sites, and 2) chronometric determinations obtained from archaeological units with techno-complexes attributed to Neanderthals or modern humans. All this information is available in the Data.xlsx file. 

The file MainScript.R includes the functions to estimate the biomass of each herbivore species according to the Net Primary Productivity (NPP), the allometric relationships between body mass and population density, and the specific herbivore guild composition in each region. This script was used to analyse and compare the NPP and the herbivore guild composition in each biogeographic region of Europe during the Marine Isotope Stage (MIS) 3.The file HB.R reproduces the validation process of the macroecological model to estimate herbivore abundances (used in Main.R) against empirical present-day herbivore densities from a broad range of terrestrial ecosystems. 

Within the Paleoclimate folder, the file Pollen.R was used to perform pollen-based paleoclimate reconstructions with weighted averaging (WA) regressions. These predictive functions are used to estimate temperature and precipitation from the palynological fossil record in Europe. 

Within the OLE folder, the file OLE.R was used to perform optimal linear estimation (OLE) models and to compare the obtained chronologies with the outcomes obtained from Bayesian age models.  

In the "Correlations_ESF" folder there are to heavy compressed files. To run the codes properly, it is necessary to first decompsress any document and to save all files within the same folder. The “Output_Experiment_A_B_C_FC1&2” file is in Excel Binary Workbook format (.xlsb) because it is a large-sized document. Before running the codes within this folder, you first have to save/convert this file into .xlsx format. There is a "README" file to help you with these two steps. Once these steps and requirements are met, the file "Correlations_ESF.R" can be run to perform Eigenvector Spatial Filtering analyses that assess the correlation between the end of the techno-complexes associated with Neanderthals, those associated with AMH, and the productivity of the ecosystems in each European region.

As the data and codes in this repository are complete, it can be reproduced with only an R environment (tested for R v4.2.0) in RStudio. The necessary package dependencies are documented in each .R file. 
The content of this repository was made possible thanks to funding from the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation programme (grant agreement No. 818299) for the SUBSILIENCE project
