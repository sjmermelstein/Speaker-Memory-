# Speaker-Memory-
Contains code and data for Mermelstein et al. 2020 published in JEPG
Supplementary Materials for “She told me about a singing cactus: Enhanced memory for the speakers of counterintuitive versus ordinary concepts” 

Each folder contains all data, study materials, and data wrangling code for each Experiment.

Within each folder, the sub-folder Data contains the raw data CSV, the RStudio code TXT, and the organized dataset CSV the code generates. Note that the Stimuli CSV also needs to be imported into R for the code to work.

The sub-folder Experiment contains the Qualtrics .qsf file that includes all the materials and runs the study. 

CODEBOOK for interpreting the organized datafile 



ResponseId —> Each participant’s unique identifier
Animal —> Attribution accuracy for CI animals 
Artifact —> Attribution accuracy for CI artifacts  
Object —> Attribution accuracy for CI objects 
Plant —> Attribution accuracy for CI plants 
Biology —> Attribution accuracy for violations of biology
Physics —> Attribution accuracy for violations of physics 
Psychology —> Attribution accuracy for violations of psychology
INT —> Attribution accuracy for all ORDINARY concepts 
MCI —> Attribution accuracy for all COUNTERINTUITIVE concepts 
age —> In years
sex —> 1 = male, 2 = female 
race —> 1 = white, 2 = hispanic, 3 = black, 4, 5, 6 = south, southeast, or East Asian, 7 = other
V1-1AC —> attention check question 1 accuracy 
V1-2AC —> attention check question 2 accuracy
V1-3AC —> attention check question 3 accuracy
V1-4AC —> attention check question 4 accuracy
AC —> attention check question question proportion correct 
Version —> Stimuli List 1 or 2 
Order —> Task version 1, 2, 3, or 4 

1_Test blockV1_INT —> 24_Test blockV1_MCI: Raw data for each trial 

Breach —> Attribution accuracy means for CI breaches 
Transfer —> Attribution accuracy means for CI transfers  


For Experiment 2a-b, use  

Condition —> Person (1), 2a: Place / 2b: Date (2) 

For Experiment 3, use the combined subfolder for analyses 

.T1 = first attribution test phase after 20 mins

.T2, second attribution test phase after 48hours 

