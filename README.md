Replication Package for the paper entitled"*Beyond Words: Stylometric Analysis for Detecting AI Manipulation on Social Media*"

**Dataset:** To answer the research questions, we considered two different datasets. The first is the same one used in: "*S. Cresci, R. Di Pietro, M. Petrocchi, A. Spognardi, and M. Tesconi, “The paradigm-shift of social spambots: Evidence, theories, and tools for the arms race,*” in Proceedings of the 26th international conference on World wide web companion, 2017, pp. 963–972",  which comprises actual human accounts with numerous tweets.  The chatGPT dataset is produced using the GPT-4 model.
The tweets and features extracted contained in the two datasets are listed in detail in the following files:
1.  The StylometricFeatures.csv file represents the experimental file With Account, Tweets, Class, and 22 features Exactracted;
2. The Accounts.csv file represents the experimental file for Accounts Identification. Mean and Standard Deviation values are calculated based on StylometricFeatures.csv;
3. The ReducedAccounts.csv file represents the experimental file (25 Features) for ReducedAccounts. The features are selected based on MDA;
4. The Tweets.csv file represents the selected tweets (20,000 tweets) file for Tweets identification. The features are selected based on MDA;
5. The ReducedTweets.csv file represents the  reduced tweets features  (15 Features) selected based on MDA.

**Detection Techniques:** To address RQ1, and RQ2 and to detect the bots and chatGPT-generated tweets using stylometric features, we chose five supervised machine learning (ML) models, namely Linear Support Vector Machine, Support Vector Machines with RBF kernel, Logistic Regression, Decision Tree, and Random Forest, organized all in  .ipynb files:
1. Consistency_Analysis(RQ_1).ipynb;
2. Decision_Tree(RQ_1&2).ipynb;
3. LogisticRegression(RQ_1&2).ipynb;
4. RandomForest(RQ_1&2).ipynb;
5. SVMLinear(RQ_1&2).ipynb;
6. SVM_RBF(RQ_1&2).ipynb

**Feature Importance and Selection:** To perform feature selection based on MDA (Mean Decrease Accuracy) we have a file i.e., Features_Selection_Based_On_MDA.ipynb
To perform feature ablation we have a file i.e., AblationStudy.ipynb. Using the ablation technique, we analyze feature contributions to model accuracy and classification. For simplicity in the paper, we show the top 10 features with scores in each model in the Table.
Finally, to assess whether the variations in the outcomes of machine learning models are statistically significant, we conduct Friedman’s test on the F1 measure. To perform the Friedman test and Nemenyi post hoc analysis, we have Friedman's_Test_&_Post_Hoc_Analysis.ipynb file.

**Additional File:** The graphical representation of top features is provided in the extra file OccurenceBasedOnAblation.ipynb to visually show the overall contribution of the top 10 features to accounts and tweet identification.
   
   
   







