# RNNs-Transformers-and-NLP-Application

Task 1: Sentiment Analysis

The IMDB movie review sentiment classification dataset contains 25,000 reviews of popular movies in the training split and another 25,000 in the testing split. Each review is labeled as either positive or negative. The task is to predict the label (positive/negative) from a given movie review.

The team is required to construct a text classification workflow from scratch, which includes the following steps:

Tokenization: Convert the raw text of movie reviews into a tokenized format suitable for further processing.
Building a CNN-LSTM Model: Design a neural network architecture combining Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) layers to process the tokenized reviews and make predictions.
Loss Function: Specify an appropriate loss function for sentiment classification.
Feeding Train/Validation Data: Prepare the training and validation data and feed it into the model for training.
Modelfit: Train the model using the prepared data and the specified loss function.
Plotting Confusion Matrix: Evaluate the model's performance by plotting a confusion matrix to assess its accuracy and ability to classify positive and negative reviews.
Identifying Correctly and Incorrectly Classified Reviews: List several reviews that were correctly and incorrectly classified by the model.
The team should attempt to achieve a validation accuracy of 90+% through the use of pre-trained word embeddings, fine-tuning, or any other suitable techniques. Useful links are provided to guide the team during this task.

Task 2: squSeq Model

The "ted_multi_translate" dataset is a multilingual (60 language) dataset derived from TED Talk transcripts. The task is to construct a squSeq model for this dataset, which can be used for various natural language processing applications such as language translation, image captioning, conversational models, and text summarization.
