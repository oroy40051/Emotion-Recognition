# Emotion-Recognition
Emotion Recognition( FER-2013 71% Accuracy)
Just using google collab an accuracy of 64% was achieved on a subset of the FER -2013 Dataset
There are two batches of images in the notebook, X_train1 and X_train2
Google collab pro can handle the larger X_train1 batch of augmented images
Normal Collab can handle only some augmentations (X_train2)
The notebook shows performance on X_train2
Run everything with X_train1 if you want to see the 70+ % validation accuracy
Best model is an ensemble of Resnet,VGG16 and a deep CNN where hyperparameters were tuned with bayesian optimiaztion.
Just the bayesian optimized deep CNN gives very good performance 69% + so that can be tried by itself.
You can play around with the Bayesian optimized deep CNN and the ensemble to see which could give better results more efficiently.
I got a kaggle score of 69% on a private competition where the test data was only around 4000-5000 images showing good generalization of the model.
