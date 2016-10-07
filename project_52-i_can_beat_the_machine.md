# I can beat the machine

## Introduction

Once upon a time, Skynet wanted to rule the fashion world and decide for you which clothes you should wear. In order to prevent the fashion Judgment Day, save mankind and probably all the pixels in it, we reprogamed one of Skynets evil fashion killing machines that was sent to dress us from the future. We did this to help us predict the trends and save John COnnor from wearing yellow with pink. It's is up to us to rage against the machines.

## Description

I can beat the machine consists of analysing the dataset provided by sonae and apply advanced algorithms to predict whether a product will be a "flop". In the train_test dataset we obtained 94% accuracy, with a ROC area of FIXME. Besides these metrics we analysed the confusion matrix and precision.

What did we do?
  * Using weka we performed feature selection (rank with gain info) to decide which features are the most relevant to classify our data.
  * We changed some of our features from nominal to numeric.
  * We perfomed cross validation over the dataset provided. 
  * As the dataset is very imbalanced, we performed over-sampling.
  * We performed, again, cross validation over the balanced dataset. 

To achieve this, we resorted to different tools, namely, weka for feature selection and run some of the models and scikit learn (python library).


## Team

 * Afonso Tinoco https://pixels.camp/xtrm0
 * António Lopes https://pixels.camp/antoniovilarinholopes
 * Filie Casal https://pixels.camp/fcasal
 * Pedro Adão https://pixels.camp/pedromigueladao

