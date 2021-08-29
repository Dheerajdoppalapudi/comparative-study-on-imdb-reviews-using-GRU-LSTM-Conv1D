# comparative-study-on-imdb-reviews-using-GRU-LSTM-Conv1D
Have a look at this [notebook](https://github.com/Dheerajdoppalapudi/Sentiment-Analysis-NLP-IMDB-dataset) wherein i have demostrated sentiment analysis using neural networks before deep diving into this notebook.

This is a comparaive study of how accuracy and validation loss vary on IMDB data set using GRU(Gated recurrent units), LSTM(long short-term memory) and 1D convolution layer.
Recurrent Neural Networks suffer from short-term memory. If a sequence is long enough, they’ll have a hard time carrying information from earlier time steps to later ones. So if you are trying to process a paragraph of text to do predictions, RNN’s may leave out important information from the beginning. so we use GRU, LSTM and Conv1D models to carry information througth the sequence.

# GRU
--> GRU and LSTM are very similar they also produce similar results GRU's can be considered as the simpler version of LSTM 
    refer [this link](https://towardsdatascience.com/understanding-gru-networks-2ef37df6c9be) to understand how GRU works.

# LSTM
--> Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems. LSTM are mostly used to machine translation, speech recognition, speech synthesis, and text generation and more.

The below picture shows the difference between the LSTM and GRU
![image](https://user-images.githubusercontent.com/63925819/131250721-86dfc443-4451-4a68-bb8f-34ffefc067d2.png)

References: <br />
http://colah.github.io/posts/2015-08-Understanding-LSTMs/ <br />
https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21
