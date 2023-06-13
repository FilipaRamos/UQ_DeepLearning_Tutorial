# Uncertainty Quantification for Deep Learning: A Practical Review

Repository hosting the code for "Uncertainty Quantification for Deep Learning: A Practical Review".

#### Datasets

Currently we only support a regression dataset that features real estate prices (from Kaggle). The csv can be found within the datasets folder.

#### Model

We implement a simple multi-layer perceptron in all tutorials and fixate training to 200 epochs with a batch size of 64. These parameters can be optimised, we have not done so since the objective is to showcase the estimation of the uncertainty rather than obtaining significant accuracy performance.


#### Relevant Dependencies

A list of some of the most relevant dependencies of the tutorials is as follows:

+ numpy
+ seaborn
+ pathlib
+ torch
+ sklearn
+ tqdm
+ pandas