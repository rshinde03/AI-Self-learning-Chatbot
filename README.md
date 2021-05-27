# AI-Self-learning-Chatbot

The dataset requires two files *movie_converstions* and *movie_lines*. The movie_converstions file was large and not supported by GitHub so a compressed zip version of it is present in the *movie_converstions.zip file*. 

The code files are as follows:

## 1) Chatbot with glove embeddings and LSTM

This file contains the model trained by using LSTM using the glove embeddings. The file used for loading the glove embeddings is *glove.6B.50d*. The model is trained using 100 epochs which requires a lot of time so we have saved the trained model in *lstm_model_glove_embeddings.h5* file. This model can be loaded from in *lstm_model_glove_embeddings.h5*  provided in the folder and then the user can chat with the chatbot.

## 2) Chatbot with skip-gram embeddings and LSTM

This file contains the model trained by using LSTM using the skip-gram embeddings. The model is trained using 100 epochs which requires a lot of time so we have saved the trained model is *lstm_model_skip_embeddings.h5* file. This model can be loaded from *lstm_model_skip_embeddings.h5* file provided in the folder and then the user can chat with the chatbot.

The *glove.6B.50d* file is very large and could not be uploaded even after compression. It can be found at this link https://www.kaggle.com/watts2/glove6b50dtxt
