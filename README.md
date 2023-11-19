# AI-MachineLearning 
This is the link to the project folder that contains all the dataset and details -https://drive.google.com/drive/folders/1GsgroWjSsaBYAr63CXYPew1f_8kd8JKk?usp=sharing

Project Details
The dataset we are working with captures credit card transactions from Europe in September 2013, recorded over two days. It's quite extensive, containing 284,807 transactions, but only 492 of these are actual frauds. This creates a stark imbalance, as fraudulent transactions comprise just about 0.172% of the total.
The data mainly consists of transformed numerical variables. These have been processed through Principal Component Analysis (PCA), resulting in features labeled from V1 to V28. These features' specifics and original forms are undisclosed due to privacy concerns. Alongside these PCA-transformed features, there are two original ones: 'Time', which tells us the time elapsed since the dataset's first transaction in seconds, and 'Amount', which is the value of the transaction. The ‘Amount’ feature is particularly interesting for models that factor in transaction costs.
The key variable to focus on is labeled 'Class'. This is what indicates whether a transaction is fraudulent or not, with 1 representing fraud and 0 for legitimate transactions.
In our project, we plan to explore and evaluate a variety of machine learning algorithms to determine which one yields the highest accuracy for our specific dataset. We will be implementing and comparing different algorithms, such as decision trees, logistic regression, and artificial neural networks. By doing so, we aim to not only identify the most effective algorithm in detecting fraudulent transactions but also to gain insights into the behavior and performance characteristics of each model under study. This comparative analysis will be instrumental in understanding which model adapts best.

Dataset Source
The source of the dataset for our project is Kaggle.
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
