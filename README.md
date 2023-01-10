# 2019-Kaggle-Comp-Skin-Cancer-Classification
Classification of skin lesions has benign or malignant. Very simple implementation using TF Hub's efficientnet b0, able to achieve very competitive results

Could have very easily expanded on the feature extraction layer from efficientnet, top results were achieved using ensembles of neural networks and transformers, but this was just a simple walkthrough to show process and that decent results can be obtained quite easily.

92% AUC on test set in best model.

Note that this isn't exactly the same dataset as the one for the 2019 competition. I didn't have the labels for the competition test set, so I had to split the data into training, validation, and testing. therefore, it makes sense that I am seeing slightly lower metrics since there are fewer data to train on.
