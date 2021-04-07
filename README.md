Origional Dataset files are stored in Below location:  
https://drive.google.com/drive/folders/1f3W1Wnp07tXey7JIlOPsye29W52SBcMc?usp=sharing

Data/CombinedALLData.csv is the origional dataset file.

This file can be downloaded using above link and save in the Data folder in location of your Notebook.


To run the project, you should do the following:

1. Execute the DataSampling.ipynb file
    This fill will perform data filtering based on the Tag frequency in a data. 
    After execution of this file you can see new file is been created at Data/QuestionsFrequent.csv
    QuestionsFrequent.csv file contains the filtered data of 83156 questions. 
    This file is also available at the link shared above. If one wants to skip this step then they can download  
    QuestionsFrequent.csv file from that location and save in the Data folder

2. Execute the StackOverflowDataProcessing.ipynb 
    This fill will perform data preprocessing activity on the questions from the file Data/QuestionsFrequent.csv. 
    After execution of this file you can see new file is been created at Data/SO_ProcessedData.csv
    SO_ProcessedData.csv file contains the Pre-Processed data of 83156 questions. 
    This file is also available at the link shared above. If one wants to skip this step then they can download  
    SO_ProcessedData.csv file from that location and save in the Data folder

3. Run the KMeansClusteringPrediction.ipynb file
    This file will perform the K-Means Clustering algorithm and you can view the results of K-means clustering in the same file

4. Run the LDAPrediction.ipynb file
    This file will perform the LDA topic modelling algorithm and you can view the results in the same file
 
 The project results will be sucessfully obtained by following above steps. 
 
 In the Project we have performed some additional activities such as finding the optimal number of clusters using Elbow method
 and get the best estimator model of LDA using GridsearchCV.
 
 Our results of both the methods can be visualise from the below files
 ElbowMethod.ipynb
 GridSearchCV_LDA.ipynb
 
 Note Executing of both the files takes long time. For our version of the dataset both of the execution took minimum 6-7 hours. 
 
 If you want to execute these files then follow the below steps:
 
 1. Execute the ElbowMethod.ipynb file 
     After successful execution results can be visualise in the same file 

 2. Execute the GridSearchCV_LDA.ipynb file 
     After successful execution results can be visualise in the same file 



