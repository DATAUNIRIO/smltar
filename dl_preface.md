# (PART) Deep Learning Methods {-}

# Forewords {-}

In this last section of the book we will follow the same style as the last section as we are still trying to create accurate predictions, 
but we are switching our attention to deep neural networks.
This section will act as the first section where we will use what we have learned about text and put it to use in a modeling context.
This section will focus on bag-of-words and word embeddings using CNN, RNN and LSTMs.

Everything before you start to fit a model it is essential to consider how algorithmic bias is represented.
Rachel Thomas proposed a checklist in [ODSC West 2019](https://opendatascience.com/odsc-west-2019-keynote-rachel-thomas-on-algorithmic-bias/) that one can use to get an idea of how the bias can be included.

1. Should we even be doing this?
1. What bias is already in the data?
1. Can the code and data be audited?
1. What are the error rates for sub-groups?
1. What is the accuracy of a simple rule-based alternative?
1. What processes are in place to handle appeals or mistakes?
1. How diverse is the team that built it?

And lets quickly talk about each point.
TODO

For the following chapters, we will use tensorflow with keras framework to do preprocessing, modeling and evaluation.

TODO add pro and cons table for differences between deep learning and non-deep learning
