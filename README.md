# Sarcasm Detection :
### An AI model project made for detecting sarcasm in news headlines 
# From understanding that detecting sarcasm requires common sense knowledge, without which the model might not actually understand what sarcasm is and may just pick up some discriminative lexical cues. Due to these limitations, it has been difficult to understand and interpret the elusive concept of sarcasm. To tackle these challenges, I will summarize this project as follows:

 ### 1-We first introduce a high-quality and (relatively) large-scale dataset for sarcasm detection, Thanks to (kaggle.com), Then we try to further prepare the Data to fit each model that we are going to train to remove all stop-words and weird characters(? ! , - …), Then we split the data into training, test, and cross-validation  sets.

### 2-Next, we use different Neural Networks  to showcase how we can reliably train a deep learning model on the dataset and produce qualitative analyses to interpret the concept of sarcasm through each module.

### 3-Lastly, We try a variety of hyperparameters to limit the effect of overfitting and reach the best possible prediction, the most accurate model, and the minimum loss across both the validation and the test sets.

# in this project we tried three different types of Neural Networks and tried to compare our results using performance charts and confusion tables, The three models are as follows :

### 1-A Multi-layer Perceptron Classifier model Using Scikit learn.

### 2-A Sequential Model Using Embedding, Global-pooling, Batch Normalizing, Drop out,  and Dens layers all from Tensorflow.

### 3-An RNN model using LSTM, Batch Normalizing, Drop out, and Dens layers from Tensorflow.

