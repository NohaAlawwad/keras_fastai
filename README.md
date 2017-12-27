# keras_fastai
### Introduction
A series of machine learning scripts in Jupyter notebooks using *Keras &amp; Theano* to solve Kaggle challenges, based on [an excellent course by Jeremy Howard](http://www.fast.ai/).

Focuses mainly on 2 Kaggle competitions - the [Dogs vs Cats Redux](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition#description) classification challenge and the (Statefarm Distracted Driver Detection)[https://www.kaggle.com/c/state-farm-distracted-driver-detection].

[sample image]: https://kaggle2.blob.core.windows.net/forum-message-attachments/116859/4125/pred7.png "Statefarm distracted driver sample image"

### Details
The project consists of 6 notebooks designed to run on a Theano backend with a Tesla K80, using Python 2.7 via Conda. This because I usually use Python 3.5-3.6 and create separate virtualenv's and wanted try something different. Full requirements can be found in req.txt (created via pip freeze).

These notebooks are the result of following fastai's philosophy of recreating the provided lesson notebooks from scratch adding one comments and experiments. We start with simple convolutional neural networks (CNNs) implemented in various ways, from pure python -> Theano -> full Keras API. We finish with various recurrent neural networks, LSTMs & GRUs.

A lot of emphasis has been put on proper preprocessing & visualisation both in the context of image classification and NLP.

Working on this was a really great experience, I deeply recommend this course (especially as a follow up to the classic ML course by Andrew Ng) as well as its second edition, which moves towards Tensorflow and generative adversarial networks. 
