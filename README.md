1. The StylometricFeatures.csv file represents the experimental file for With Account, Tweets, Class, and 22 features Exactracted.
   1.1. The Accounts.csv file represents the experimental file for Accounts Identification. Mean and Standard Deviation values are calculated based on StylometricFeatures.csv.
   
   1.2 Hence, we contained all the tweets in one file i.e. Datasets (where chatGPT tweets are represented by 1 and human by 0). The main source of human datasets is http://mib.projects.iit.cnr.it/dataset.html which is considered the best source for genuine and verified human-operated accounts.

3. The SingleTweets.csv file represents the experimental file containing the features extracted for Tweets Identification  (Setup - 2). 

4. The Other Two files I.e., ReducedAccounts.csv and ReducedTweets.csv are the files with reduced features set for additional experiments To Identify Accounts and Tweets Respectively.

5. All the .ipynb files are the machine learning files for RQ1. and RQ2.
   
   4.1 Consistency_Analysis(RQ_1).ipynb is to access the RQ1.
   
   4.2 The following files are used to access RQ1.1 & RQ2.

   Decision_Tree(RQ_1_1&2).ipynb, 
   LogisticRegression(RQ_1_1&2).ipynb, 
   RandomForest(RQ1_1&2).ipynb, 
   SVMLinear(RQ1_1&2).ipynb, 
   SVM_RBF(RQ1_1&2).ipynb

   4.3 To perform feature selection based on MDA we have a file i.e., Features_Selection_Based_On_MDA.ipynb
   
   4.4 To perform feature ablation we have a file i.e., AblationStudy.ipynb. This file identifies the importance of each single feature in each model. For Simplicity In the paper, we show the top 10 features with scores in each model in the Table. 

   4.5 To perform the Friedman test and Nemenyi post hoc analysis we have Friedman's_Test_&_Post_Hoc_Analysis.ipynb file.
   
   4.6. Additional File: The graphical representation of top features is provided in the extra file OccurenceBasedOnAblation.ipynb to visually show the overall contribution of the top 10 features to accounts and tweet identification.
   
   
   







