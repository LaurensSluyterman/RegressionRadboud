# Neural network introduction

This repository contains a basic introduction to 
constructing and training a neural network. In order
to get start, make sure all the relevant packages 
are installed. The packages that are used in this
repository can be found in the *requirements.txt* 
file.

This repository is still under construction. 
More examples may be added soon and the
existing examples are likely to be improved.
### Boston housing regression
Start with this notebook. We go through a typical
work-flow of training a neural network. We
start with some very basic data analysis and
pre-processing. 
In a serious project, this step should be much
more elaborate. Are there missing values? Are
their errors in the data? Can we spot some trends 
before starting? This is not implemented in this 
basic notebook.

We then construct and train a simple neural network.
What will see while analyzing it, is that it is 
overfitting a lot. This is a very typical approach
that needs to be addressed by regularizing the 
network, for instance through l2-regularization,
early stopping, or dropout. This is not 
implemented in this notebook but can be added as an
exercise. In general, a good hyperparameter search
should always be part of your workflow. Neural 
networks rarely perform well out of the box and 
should be carefully tuned by using either a
train/test/validation split or cross-validation. 
This important step is not implemented in this
introduction.

Lastly, we will try to get a basic insight into how
the network's predictions depend on the covariates.

### Boston housing classification
Using the same data set, we will see how we can
use a neural network for a classification setting.
We create a classification problem by considering all
the houses with a price above 25 as class 1 and all other houses
class 0. The results get compared to a generalized
linear model.

