# (PART) Machine Learning Methods {-}

# Forewords {-}

This section will act as the first section where we will use what we have learned about text and put it to use in a modeling context.
This chapter will mostly be focused on bag-of-words models using methods like; Naive Bayes, Support Vector Machines (SVM) and regularized regressions models like glmnet.

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

For the following chapters, we will use [tidymodels](https://github.com/tidymodels) framework to do preprocessing, modeling and evaluation.
