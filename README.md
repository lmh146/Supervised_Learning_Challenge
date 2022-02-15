# Supervised_Learning_Challenge
---
## Overview
This project looks to predict credit loan risk levels by comparing two models in a supervised machine learning method. It looks at classifying using logistical regression in contrast to the random forest classifier on both unscaled and scaled data. Before, during, and after this project, I made predictions on what was likely to occur. Said predictions can be found below.

## Predictions
### Before Creating the Models on Unscaled Data
From my understanding of both the logistic regression and random forest classifier models, I predict the random forest classifier model will perform better with the data we have. Considering the number of features we are imputting I believe the random forest classifier will be better able to navigate through the data and numerous categories. With this being said, I have a suspicion that the logistic regression will deceptively perform better with the unscaled data simply because the true or false output of the random tree may be complicated by the varying scales.

### Before Creating the Models on Scaled Data
I believe following the scalerization of the data, the logistical regression score will improve while the random forest classifier models may decrease its score. The logistical regression utilizes a linear regression within its formula and so having a scaled dataset will condense the points. This will allow for a stronger linear result and in return create a more accurate logistical regression. The reason the random forest classifier score is likely to decrease is due to the nature of the classifier. Random forest classifier uses a true or false option to classify so running higher numbers than 0 or 1 would result in false and be ignored entirely. The scaled data will likely give it a more complicated field to work through and therefore lower its score.

### After Creating Both Models on Both Datasets
The random forest classifier maintained an R2 score of 1.0 for both the scaled and unscaled data. This was not my prediction in the slightest. The model proved to predict well regardless of if the data was scaled or unscaled. This was not the case for the logistical regression. Part of my prediction was correct that the logistical regression would perform better with the scaled data as it went from 0.5 on the unscaled testing to 0.99on the scaled testing data but it never out performed the random forest classifier. I believe I should revisit these models and understand their functionings a bit better to make stronger predictions in the future.
