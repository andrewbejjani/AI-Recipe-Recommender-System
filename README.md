# AI-Recipe-Recommender-System
* Dataset was obtained from an online kaggle source **[Food.com Recipes and Interactions](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions?select=RAW_interactions.csv)**, where we preprocessed datasets: "RAW_interactions.csv" and "RAW_recipes.csv", which were then used for training.
* FeedMe_Preprocessing.ipynb contains the code where we preprocessed both online datasets to obtain a much useful dataset to train and test.
* FeedMe_NN.ipynb contains the code where we trained a Neural Network on the preprocessed data using two different optimizers and visualized train and validation accuracy and loss.
* FeedMe_Similarity.ipynb contains the code where we used the Jaccard Similarity Metric to find the closest recipes to 1 recipe based on its ingredients. 
