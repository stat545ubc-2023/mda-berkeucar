# MINI DATA-Analysis 1, STAT 545A 
## Berke Ucar - M.Sc. Bioinformatics

This repository is where the mini data project 1 and 2 of STAT 545A class has been stored under the name of Berke UCAR. The repository mainly contains the data exploration, cleaning, tidying, model fitting, external file reading and writing for the dataset _steam\_games_ of [_data\_teachr_](https://github.com/UBC-MDS/datateachr) package. It also additionally contains the dataset selection procedure before selecting _steam\_games_ done in Milestone 1.  

In Milestone 1, data exploration of different datasets have been done and one of the datasets was intended to be performed on. Milestone 1 contains the dataset graphing and exploration steps. Furthermore, it also provides guidance to the Milestone 2.

In Milestone 2, selected dataset has been studied more deeply. The summary statistics and graphing have been applied to data to answer the 4 research questions designated when the Milestone 1 was turned in. Furthermore, this milestone also include dataset tidying approaches. Model fitting and prediction approaches have been shown in this milestone for one of the research questions. Last but not least, csv writing and rds file reading and writing have been exhibited in this milestone.

This repository contains 3 folders on its higher level:
1. *mini-project-1*: Contains the files for Milestone 1 - _mini-project-1.md_, _mini-project-1.rmd_, _mini-project-1\_files_, _README.md_
2. *mini-project-2*: Contains the files for Milestone 2 - _mini-project-2.md_, _mini-project-2.rmd_, _mini-project-2\_files_, _README.md_
3. *output*: Contains the csv and rds outputs of _mini-project-2.rmd_ knits - _output\_q41.csv_ and _output\_q42.rds_, _README.md_

In order to engage with this repository, only thing that is needed to be done is to navigate into either _mini-project-1/mini-project-1.md_ or _mini-project-2/mini-project-2.md_ file. This file contains the github markdown version of the originally prepared _mini-project-1/mini-project-1.rmd_ and _mini-project-2/mini-project-2.rmd_ files. One can see the underlying code of  _mini-project-1/mini-project-1.md_ by navigating into _mini-project-1/mini-project-1.rmd_  and do the corresponding for 2nd milestone versions. Furthermore, the repository also contains the _mini-project-1/mini-project-1\_files_ and _mini-project-2/mini-project-2\_files_ folders, which accommodates the plots of the _mini-project-1/mini-project-1.md_ and _mini-project-2/mini-project-2.md_ files respectively. One can check the plots from these folders in a more detailed manner. 

In order to locally run _mini-project-1/mini-project-1.rmd_ file, one should open this file in RStudio and knit the document using the *Knit* button located on the navigation bar. Furthermore, each knit generates a new _mini-project-1/mini-project-1.md_ file and _mini-project-1/mini-project-1\_files_ folder containing the _mini-project-1/mini-project-1.md_ file's plots. So, if you need to preserve the previous run's output, you can change the .rmd file's name temporarily. This is also functional for the 2nd milestone rmd file as well. However, additionally, knitting _mini-project-2/mini-project-2.rmd_ file also overrides the files contained in _output_ folder. So, one needs to save the current files inside _output_ folder to another directory to preserve them. This folder contains the answer of question 4.1 _output\_q41.csv_ and the the answer of question 4.2 _output\_q42.rds_
for MS2.

All _README.md_ files explain the directories that are located in.
