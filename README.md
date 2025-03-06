# P194CS
Repository containing my work for PSTAT194CS: Computational Statistics &amp; Special Topics

File Descriptions:
* wikipedia: contains the data used in the final project files. 
  * citing.txt: includes citation to original research for which the data was gathered
  * README.txt: description of the data
  * Folders for data corresponding to Wikipedia articles for chameleons, crocodiles, and squirrels. each folder contains a file wit the following info
    * edges.csv: csv file containing edge data for the network of articles. each observation corresponds to a hyperlink connection between two articles (represented with an id number)
    * features.json: json file with node features. node features correspond to specific keywords found in each article (represented with the same id number as edges.csv)
    * target.csv: contains the monthly traffic for each article (represented with the same id number as edges.csv)
* Final_Project.Rmd: final deliverable for the project, includes specific visuals and analysis
* FinalProjectWriteUp_Group5_Lucas.Rmd: contains analysis and scripts from our work on the project
* FinalReportWithStuff.Rmd: similar to previous file, contains incomplete work from the draft phase of our final project
* MidtermProject.Rmd: personal project assigned as our midterm, contains different Monte Carlo techniques used to sample from complex statistical distributions
* PSTAT194CS-Final-Project---Group-5.Rmd: knitted pdf of our final project
