# Cultivating Creativity Improves Middle School Students' Computational Thinking Skills
This repository contains data files used for the analyses in the above paper, written by R. Israel-Fishelson and A. Hershkovitz.

The paper focuses on analyzing the impact of an intervention program to increase creativity on the acquisition of CT, using learning analytics techniques. For the statistical analyses we used JASP version 0.14.1 and IBM SPSS version 25. We used RapidMiner Studio for evaluating the dataset using Decision Trees. 

**Data Files:**

**TTCT_AUT_LOG.csv**: Contains all the information about the users who participated in the experiment, including background characteristics and all the metrics of creativity, computational thinking and computational creativity, as emerged from the pretest and posttest. 

**TTCT_AUT_LOG_RG only.xlsx**: Contains all the information about the users in the research group. That is, users who conducted the pretest and the posttest and also took part in the intervention sessions. 

**Decision Trees-Based Prediction.rmp**: Contains a RapidMiner process representing a decision tree model for predicting CT and Computational Creativity measures in the posttest task.
Note: to run the process in RapidMiner, make sure to load the TTCT_AUT_LOG_RG only.xlsx from your local repository (click on the “Read Excel” operator and then change the “excel file” on the Parameters window. 
