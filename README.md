1. The StylometricFeatures.csv file represents the experimental file With Account, Tweets, Class, and 22 features Exactracted.
   
   1.1. The Accounts.csv file represents the experimental file for Accounts Identification. Mean and Standard Deviation values are calculated based on StylometricFeatures.csv.

   1.2. The ReducedAccounts.csv file represents the experimental file (25 Features) for ReducedAccounts. The features are selected based on MDA.

   1.3. The Tweets.csv file represents the selected tweets (20,000 tweets) file for Tweets identification. The features are selected based on MDA.

   1.4. The ReducedTweets.csv file represents the  reduced tweets features  (15 Features) selected based on MDA.

   1.5 Hence, we contained all the tweets in one file i.e. Datasets (where chatGPT tweets are represented by 1 and human by 0). The main source of human datasets is http://mib.projects.iit.cnr.it/dataset.html which is considered the best source for genuine and verified human-operated accounts.

3. All the .ipynb files are the machine learning files for RQ1. and RQ2.
   
   2.1 Consistency_Analysis(RQ_1).ipynb is to access the RQ1.
   
   2.2 The following files are used to access RQ1.1 & RQ2.

   Decision_Tree(RQ_1_1&2).ipynb,
   
   LogisticRegression(RQ_1_1&2).ipynb,
    
   RandomForest(RQ1_1&2).ipynb,
   
   SVMLinear(RQ1_1&2).ipynb,
   
   SVM_RBF(RQ1_1&2).ipynb

   2.3 To perform feature selection based on MDA we have a file i.e., Features_Selection_Based_On_MDA.ipynb
   
   2.4 To perform feature ablation we have a file i.e., AblationStudy.ipynb. This file identifies the importance of each single feature in each model. For Simplicity In the paper, we show the top 10 features with scores in each model in the Table. 

   2.5 To perform the Friedman test and Nemenyi post hoc analysis we have Friedman's_Test_&_Post_Hoc_Analysis.ipynb file.
   
   2.6. Additional File: The graphical representation of top features is provided in the extra file OccurenceBasedOnAblation.ipynb to visually show the overall contribution of the top 10 features to accounts and tweet identification.
   
   
   







