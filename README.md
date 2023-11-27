# yelp_dataset_text_analytics
Repo for text analytics project
This is our code base for our Final Project for ISE 540 (Text Analytics), Fall Semester 2023. 


Group Members: 
- Shree Vaishnavi Bacha
- Vishal Patil
- Yash Verma
- Revanth Yamani
- Janis Yue 

Folders:

- datasets:  folder containing the final labelled dataset in .csv format (contains 5000 datapoints)  
- pilot_testing_notebooks: folder containing the initial notebooks that we used for EDA and getting used to the dataset   

Files Included: 

- sampling.ipynb: Notebook containing code to sample the the dataset  
- Final_Multiclass_Models.ipynb: Notebook containing code for the classical ML models (Naive Bayes, SVM, KNN, Decision Trees)   
- BERT_multiclass_multilabel_classification.ipynb: Notebook containing code for BERT model training and predictions on unlabelled dataset  
- BERT_model_future_work.ipynb: Notebook containing code for improving BERT model performance using techniques like different imputed values and data augmentation using nlpaug library  
- Correlation&RegressionAnalysis.Rmd: R code used to perform correlation and regression analysis on predictions on validation dataset (labelled data) and test dataset (unlabelled data)  
- Statistical Testing.ipynb: Notebook to run the statistical test for analysing if there were significantly higher proportion of reviews mentioning the word "husband" than the word "wife"  



Some dataset files were too large to upload to github. To access those files, we have uploaded them to google drive and they are available at the following links: 

- Unlabeled dataset with model predictions: https://drive.google.com/file/d/1nIrQYKGNpHlATpkHNT27sFefRhpgocnW/view?usp=sharing





Usage of the Files included: 

Data Exploration: More info is given on these notebooks within the pilot testing folder.

Dataset (subset) creation, sampling 

Model training and Evaluation

R code for correlation, significance testing 

Running the code:  
The notebooks can be run on google colab directly without many modifications.  
One point to note is that the paths from where we are reading the .csv files have to be changed before running the notebooks.



