# Project summary
The purpose of the project is to detect wheat from a dataset in kaggle.
We used Faster-r-cnn for detection with ResNet backbones.
The 'train' file purpose is an example of a model which we trained to use in the ensamble.
Our best score on a submitted model (with various types of Hyper-parameters) was 0.62,
which wasnt enough for what we wanted to acheive.
Our idea was to use these trained models and not throw them away so we used everyone of them to make an ensemble of our models.
The 'inference' file demonstrate how we made the ensemble with the methods that we used.
The ensemble improved our score to 0.72 which placed us in the **top 20% of the competition.
