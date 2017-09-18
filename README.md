# Wide and Deep Network in tflearn (in Progress)
Repo to test wide and deep models in [tflearn](http://tflearn.org/), a higher level API for Tensorflow. This is an implementation of the paper [Wide & Deep Learning for Recommender Systems](https://arxiv.org/abs/1606.07792) with a Tensorflow tutorial [here](https://www.tensorflow.org/tutorials/wide_and_deep) using tf.contrib.learn. A [blog post](https://research.googleblog.com/2016/06/wide-deep-learning-better-together-with.html) is available here as well.

The dataset used is [Census Income Dataset](https://archive.ics.uci.edu/ml/datasets/Census+Income), the same one used in the Tensorflow. The aim is to predict if an individual has income over 50,000 given a range of continuous variables (age, education_num, capital_gain, capital_loss, hours_per_week) and several categorical variables. 

Many thanks to [ichuang](https://github.com/ichuang/tflearn_wide_and_deep) for which I referenced greatly when I was coding the network.

<h2>Model</h2>
The wide and deep model is a model that attempts to combine memorization (using the wide model) as well as generalization (using the deep model) to create a model that can generalize well as well as give the surprise me moment as per its original intention for app recommendations. 




