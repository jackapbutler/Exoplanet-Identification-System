# Exoplanet Identification System
Convolutional Neural Network model which classifiies transit signal data in order to accurately identify exoplanets.

1. The dataset describes the change in flux (light intensity) of multiple stars over time. The data was cleaned in the "Cleaning" jupyter notebook. This involved eliminating the noise from the transit light signals and performing stratified sampling to ensure accurate machine learning models. I became familiar with the implementation of a wide range of denoising algorithms.

2. The neural network was trained and designed in the "Model" jupyter notebook. This involved designing the neural network architecture, creating a balanced batch generator and running multiple training sessions. I also learned about measures to combat imbalanced response variables and high dimensionality within a dataset.

3. It was vital to measure success using a confusion matrix due to the imbalanced nature of the dataset.
