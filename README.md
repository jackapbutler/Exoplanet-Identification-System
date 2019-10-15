# Exoplanet_Finder
Convolutional Neural Network classification of transit signal data to find exoplanets.

1. The data was cleaned in the "Cleaning" jupyter notebook. 
   This involved eliminating the noise from the transit light signals and performing stratified sampling to ensure accurate machine learning models.

2. The neural network was trained and designed in the "Model" jupyter notebook. 
   This involved designing the neural network architecture, creating a balanced batch generator and running multiple training sessions.
   It was vital to measure success using a confusion matrix and not rely solely on an accuracy metric due to the imbalanced nature of the dataset.
