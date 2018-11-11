# Neural-Machine-Translation
[Neural Machine Translation](https://en.wikipedia.org/wiki/Neural_machine_translation) is the use of deep neural networks for the problem of machine translation.

This is an implementation of Neural Machine Translation system using Encoder-Decoder Mechanism that translates German phrases to English.
The overall implementaion is inspired from a blog post written by Jason Brownlee.

*Note : The clean data contains a little over 150,000 phrase pairs and some of the pairs toward the end of the file are very long.The problem is simplified slightly
by reducing the dataset to the 10,000 examples.*

I would encourage you to explore and develop a model on the fuller dataset as an extension.

# Dataset
The dataset is available from the ManyThings.org website, with examples drawn from the Tatoeba Project. The dataset is comprised of German phrases and their English counterparts.

The dataset used can be downloaded here : [German – English deu-eng.zip](http://www.manythings.org/anki/deu-eng.zip)

# Requirements
1. Python
2. Tensorflow
3. Keras
4. Pickle
5. Numpy
6. NLTK
