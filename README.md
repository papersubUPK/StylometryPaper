1. The Accounts.csv file represents the experimental file for Accounts Identification (Setup - 1). Mean and Standard Deviation values are calculated based on ChatGPT Datasets.csv and Human Datasets.csv files  containing Tweets, with respective Tweets ID, Accounts ID, and Features Extracted. Moreover, all the tweets are contained in one file i.e. All_Tweets.csv for experimentation.

2. The SingleTweets.csv file represents the experimental file containing the features extracted for Tweets Identification  (Setup - 2). 

3. The Other Two files I.e., ReducedAccounts.csv and ReducedTweets.csv are the files with reduced features set for additional experiments To Identify Accounts and Tweets Respectively.

4. All the .ipynb files are the machine learning files for RQ1. and RQ2.
   
   4.1 Consistency_Analysis(RQ_1).ipynb is to access the RQ1.
   
   4.2 The following files are used to access RQ1.1 & RQ2.

   Decision_Tree(RQ_1_1&2).ipynb, 
   LogisticRegression(RQ_1_1&2).ipynb, 
   RandomForest(RQ1_1&2).ipynb, 
   SVMLinear(RQ1_1&2).ipynb, 
   SVM_RBF(RQ1_1&2).ipynb

   4.3 To perform feature selection based on MDA we have a file i.e., Features_Selection_Based_On_MDA.ipynb
   
   4.4 To perform feature ablation we have a file i.e., AblationStudy.ipynb. This file identifies the importance of each single feature in each model. In the paper, we show the top 10 features with scores for each model in the Table. The graphical representation of these features is provided in the extra file OccurenceBasedOnAblation.ipynb to visually show the overall contribution of these features to accounts and tweet identification.

   4.5 To perform Friedman test and Nemenyi post hoc analysis we have Friedman's_Test_&_Post_Hoc_Analysis.ipynb file.
   
   
   







