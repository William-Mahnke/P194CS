This repository contains my midterm and final projects from PSTAT194CS: Computational Statistics (Special Topics). The aim of the midterm project was to use different Monte Carlo sampling techniques to computationally sample complex distributions. The aim of the final project (done in a group) was to perform social network analysis on a network found online.

File Descriptions:
* Final_Project.Rmd: final deliverable for the project, includes specific visuals and analysis
* Final_Project_Draft_1: similar to previous file, contains incomplete work from the draft phase of our final project
* Final_Project_Draft_2: contains analysis and scripts from our work on the project
* MidtermProject.Rmd: final file for midterm project
* Final-Project.pdf: knitted pdf of our final project
* wikipedia: contains the data used in the final project files. 
  * citing.txt: includes citation to original research for which the data was gathered
  * README.txt: description of the data
  * Folders for data corresponding to Wikipedia articles for chameleons, crocodiles, and squirrels. each folder contains a file wit the following info
    * edges.csv: csv file containing edge data for the network of articles. each observation corresponds to a hyperlink connection between two articles (represented with an id number)
    * features.json: json file with node features. node features correspond to specific keywords found in each article (represented with the same id number as edges.csv)
    * target.csv: contains the monthly traffic for each article (represented with the same id number as edges.csv)
