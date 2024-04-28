# Email-Spam-Detection
Machine learning algorithms such as SVM, Random Forest, Decision Tree, CNN, KNN, MLP and many more to predict spam emails.
Machine Learning for Email Spam Filtering: Review, Approaches and Open Research Problems
In this paper author is giving brief review on various machine learning algorithms such as SVM, Random Forest, Decision Tree, CNN, KNN, MLP and many more to predict spam emails. Author has done experiments with above algorithms by using various SPAM datasets such as SPAM ARCHIVE, SPAMBASE, LINGSPAM, PU1 and many more but we are using SPAMBASE dataset to evaluate performance of above algorithms in terms of accuracy, precision and recall.
SPAMBASE dataset saved inside spambase folder and below screen shots showing details of dataset

  
In above dataset first row contains column names as email word frequency and other rows contains probability of that word occur in email and in last column we have value as 0 or 1 where 0 indicate normal email and 1 indicate SPAM email. We will use above dataset to train all ML algorithms.
SCREEN SHOTS


To run project double click on ‘run.bat’ file to get below screen 
 
1. Upload SpamBase Dataset
The selecting and uploading ‘spambase.data’ dataset and then click on ‘Open’ button to load dataset. Then the dataset may loaded.
2.Preprocess Dataset
Preprocessing is the second module in our project. To read all values from dataset and then split data into train and test part where application used 80% dataset for training and 20% dataset for testing.
3. Run KNN, Naive Bayes & Multilayer Perceptron Algorithms
We have to run all 3 algorithms and get there prediction metrics, we got evaluation metrics such as accuracy, recall and precision for all 3 algorithms.
4.Run SVM, Decision Tree & AdaBoost Algorithms’
First we have to run Run SVM, Decision Tree & AdaBoost Algorithms. Then we got metrics for SVM, decision tree and AdaBoost algorithms.
5.Run Random Forest & CNN Algorithm
We should run Random Forest & CNN Algorithm, then  we got accuracy for CNN and random forest algorithms.
6. Accuracy Comparison Graph
In graph x-axis represents algorithm name and y-axis represents accuracy of all those algorithms and from above graph we can conclude that MLP neural network give better prediction accuracy compare to all other algorithms.
7.Recall Comparison Graph’
In graph x-axis represents algorithm name and y-axis represents Recall values of all those algorithms .
8.Precision Comparison Graph
In graph x-axis represents algorithm name and y-axis represents Precision values of all those algorithms .

SYSTEM REQUIREMENTS
HARDWARE REQUIREMENTS:
•	Processor			-	Pentium –IV
•	Speed				-    	1.1 Ghz
•	RAM				-    	256 MB(min)
•	Hard Disk			-   	20 GB
•	Key Board			-    	Standard Windows Keyboard
•	Mouse				-    	Two or Three Button Mouse
•	Monitor			-    	SVGA
SOFTWARE REQUIREMENTS:
•	Operating System		-	Windows7/8
•	Programming Language	-	Python
