# Text Summarization

In this article, We will go through explanation about sequence to sequence model. After completing this tutorial, you will know:

* Quick review why Recurrent Neural Network instead of Vanilla Neuaral Network for sequential set data.
* Sequence to sequence model implementation in a various business.
* Many type of text data vectorization in sequence to sequence model.
* The different of Abstractive and Extractive summarization.
* How to build encoder-decoder architecture for text summarization.

I recommend that you have (prerequisites):

* Familiarity with R programming
* Familiarity with neural network and in particular, Recurrent Neural Networks (RNNs). If you are not yet familiear with RNNs, I recommend reading the RNN section which will give you quick start. For you who want to dive deep to RNN architecture please look up to [this article](https://algotech.netlify.com/blog/text-lstm/).

# Dataset

In this totorial we will build a seq2seq model that can create relevant summaries for reviews written about fine foods sold on Amazon. This dataset contains above 500000 reviews, and is hosted on [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews). It's too large to attach here, it's over 300MB. After you have  finished downloading, put it on `\data\` folder.

----

Happy learning! :grin: