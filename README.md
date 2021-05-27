# AI-Self-learning-Chatbot
![](https://img.shields.io/badge/CODE-PYTHON-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/version-3.7.3-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Model-LSTM-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Embeddings-Glove-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Embeddings-SkipGram-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Domain-Chatbot-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)

Conversational based modeling is an important task in Natural Language Processing and the field of Artificial Intelligence. A chatbot that works as a conversational agent is a software designed to communicated with humans using language processing abilities and machine learning. Designing a smart chatbot has been one of the most challenging aspects in the world of AI and Natural Language Processing. Previously chatbots had been designed using handwritten rules like regular expressions. Today this approach is not feasible and does not suffice the requirements in any domain as there are many rules required to be written for a chatbot to function as a human in a conversation.

In this project, we have designed a neural network-based AI chatbot that uses LSTM as its training model for both encoding and decoding. The chatbot works like an open domain chatbot that can answer day-to-day questions involved in human conversations. Words embeddings are the most important part of designing a neural network-based chatbot. Glove Word Embedding and Skip-Gram models have been used for this task. The model was trained end-to-end without any handcrafted rules. The huge conversational dataset used for training the Long Short-Term Memory (LSTM) recurrent neural network is the Cornell Movies dataset. The chatbot self learns from the training data and answers questions that are not domain specific.

## Dataset

The dataset requires two files *movie_converstions* and *movie_lines*. The movie_converstions file was large and not supported by GitHub so a compressed zip version of it is present in the *movie_converstions.zip file*. 

## Code Files

### 1) Chatbot with glove embeddings and LSTM

This file contains the model trained by using LSTM using the glove embeddings. The file used for loading the glove embeddings is *glove.6B.50d*. The model is trained using 100 epochs which requires a lot of time so we have saved the trained model in *lstm_model_glove_embeddings.h5* file. This model can be loaded from in *lstm_model_glove_embeddings.h5*  provided in the folder and then the user can chat with the chatbot.

### 2) Chatbot with skip-gram embeddings and LSTM

This file contains the model trained by using LSTM using the skip-gram embeddings. The model is trained using 100 epochs which requires a lot of time so we have saved the trained model is *lstm_model_skip_embeddings.h5* file. This model can be loaded from *lstm_model_skip_embeddings.h5* file provided in the folder and then the user can chat with the chatbot.

## Glove Embeddings File

The *glove.6B.50d* file is very large and could not be uploaded even after compression. It can be found at this link https://www.kaggle.com/watts2/glove6b50dtxt
