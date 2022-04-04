# Machine Learning, a Bayesian Perspective - Assignement 2

## Flower Recognition

##### Authors: David Gomes and Pablo de Anta

Our project consisted in Flower Recognition, specifically 5 flowers: dandelion, daisy, rose, tulip, and sunflower. This code was utilized in order to come up with the results shown in the group's report.

The structure of this folder is as follows:

* *CNN_Flower.ipynb* : Showcases the main results of the CNNs as well as all the data treatment
* *data_preparation.ipynb* : This file is not meant to be run. It shows how the data was split into training, testing, and validation. It is also applied all the transformations used to augment the data. By running this code, the previous data will be overwritten by new one, defeating the purpose of what it was originally meant to do, create specific datasets in order to produce consistent results.
* *Naive_Bayes.ipynb* : Code implementation of the Naive Bayes in our problem using a googlenet to extract the feautures.
* *BayesianNN.ipynb* : Code implementation of a "conventional" ResNet34 and a Bayesian version of it, using variational inference.
* *training_CNN.ipynb* : Code with all the training of the CNNs
* *flowers* : Original given dataset
* *tvt_flowers* : Folder that has all the data produced from the *data_preparation.ipynb* file.
* *runs* : While training a network in *training_CNN.ipynb*, logs from tensorboard are stored here
* plots : images from *CNN_Flower.ipynb* and *t**raining_CNN.ipynb*
* data_plots : images from *BayesianNN.ipynb*
* models : stored models of the CNNs, used back in *CNN_Flower.ipynb*


*Note: In data_preparation, there is a dataset called less_aug which was only used in a beggining stage of the project and ended up not being used*
