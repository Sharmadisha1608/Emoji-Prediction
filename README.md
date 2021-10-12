# Emoji-Prediction
#### About
###### In this machine learning project, we predict the emoji from the given text. This means we build a text classifier that returns an emoji that suits the given text. Our systems should be aware of the relevant emoji to use at the proper moment.The dataset consists of 2 parts, each is used for training and testing the deep learning model.The training dataset contains 4 columns, one column being the text and the other contains IDs representing the emojis.

#### Flowchart oh the Methodology:

###### 1. Perform Exploratory Data Analysis (EDA).
###### 2. Build the classifier model.
###### 3. Train and evaluate the model.

![image](https://user-images.githubusercontent.com/56456928/136998049-22b93234-19c3-4244-9a02-27a60e2e1897.png)

###### We use word embeddings in this emoji prediction project to represent the text. The relationship between the words is represented using word embeddings. This process aims to create a vector with lesser dimensions. An embedding is a low-dimensional space into which high-dimensional vectors can be translated. Machine learning on huge inputs, such as sparse vectors representing words, is made simpler via embeddings. We use the 6B 50D GloVe vector to build the embedding matrix for the text in our dataset.

###### For this emoji prediction project, we will be using a simple LSTM network.LSTM stands for Long Short Term Network. Recurrent neural networks are a type of deep neural network used to deal with sequential types of data like audio files, text data, etc. LSTMs are a variant of Recurrent neural networks that are capable of learning long-term dependencies. LSTM networks work well with time-series data.

###### Now compile and fit our model against the embedding matrix we have computed using the training data. The categorical crossentropy is used as the loss function and Adam is used as the optimizer function. For metrics, accuracy is used.

###### In this deep learning project, we built a text classifier that predicts an emoji that suits the given text. We achieve good accuracy in the implementation, although based on requirements we can train it with larger datasets. To predict emojis, we used LSTM as LSTM networks work well with time-series data.

#### Input-Output Screenshot:


![image](https://user-images.githubusercontent.com/56456928/136998141-105cd80c-8759-4cbc-ae27-a48e73e3da8b.png)
![image](https://user-images.githubusercontent.com/56456928/136998152-9d932a5e-2281-432e-b175-cf4e882c3ac9.png)
