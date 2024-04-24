# Satellite-Land-Image-classification-using-Convolutional-Neural-Networks

### Introduction

- Utilizing remote sensing images, particularly from the EuroSAT dataset subset with three classes: "River," "Residential," and "Pasture," for image classification using Convolutional Neural Networks (CNNs).

- Pre-processing the dataset by normalizing spectral bands, dividing images into smaller patches, and training a CNN model to classify images into binary categories ("0" for not belonging to a class, "1" for belonging), enhancing accuracy through spectral and spatial information incorporation.


### Objective:
The aim of this research is to utilize deep learning techniques, specifically Convolutional Neural Networks (CNN), to train a model on the EuroSAT dataset for automated image classification. The primary goal is to achieve high accuracy in classifying satellite images into different land use and land cover types. Additionally, the model should demonstrate strong generalization capabilities on unseen data, enhancing the efficiency and accuracy of land use classification processes.



### Methodology:

- Employed the VGG-16 architecture in training the CNN model, leveraging its deep structure and proven image classification capabilities.

- Used essential libraries and Google Colab for dataset handling and preprocessing.
  
- Defined, compiled, and trained the CNN model, evaluating accuracy and plotting metrics for analysis.
  
- Demonstrated the model's classification ability on external images, showcasing its broader applicability.


### Conclusion

Our study employs Convolutional Neural Networks (CNNs) to classify images sourced from the EuroSAT dataset. This dataset serves for both training and testing the CNN model, achieving an impressive accuracy of 98%. Despite using small RGB images for training, the computational time for processing these images was slightly higher compared to standard JPG images. Ultimately, our classification model accurately categorizes input images into their binary classes [0, 0, 1] with a 98% accuracy rate.
