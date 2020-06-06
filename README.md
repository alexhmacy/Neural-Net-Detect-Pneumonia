# Detecting Pneumonia from X-Rays

## Introduction

Import, explore, clean, standardize, and model the Chest X-Ray dataset with a Keras Sequential Model. Utilize Data Augmentaton, Normalization, and Class Balancing to generate the best testing results.

We want to know, given an X-Ray, whether or not a patient has pneumonia. This inherently comes with costs-benefits which can be analyzed with confusion matrices, and roc curves. 

##  First Steps
1. Create a naive Sequential model baseline
2. Evaluate this baseline against a more convoluted model

## Developing more advanced methods
3. Normalize and augment the data, and then revisualize on a more complex model.
4. Compare/Contrast pros and cons of modeling, identify inherent problems in the data.
5. Adjust for class imbalancing; readdress data issues
6. Explore and then recommend further Data Augmentation.
7. Present conclusions and offer recommendations.

## Methodology and Approach 
This will be a supervised learning classification with three datasets: train, validation, and test. Instances are labeled by their class as either 'NORMAL' or 'PNEUMONIA'. Using a Multilayer Perceptron, my model will attempt to predict an image's class. 

## Performance Measures
Adam and Binary Cross Entropy, aided by Batch Normalization and Class Balancing.

## Conclusion & Recommendations

More data is needed. Data can either be acquired traditionally, or created using data augmentation and feature mapping.
