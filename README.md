# Batik-Patterns-Classification

This project aims to classify three famous Indonesian batik patterns—Parang, Mega Mendung, and Kawung—using deep learning techniques. The goal is to accurately recognize and classify these beautiful motifs, which vary in shape and design. By automating the identification of traditional batik patterns, we can help preserve this important aspect of Indonesian culture. I experimented with several models, including custom-built architectures and various transfer learning models, to find out which one performs best for this task.

## Dataset
The dataset, sourced from Kaggle (https://www.kaggle.com/datasets/dionisiusdh/indonesian-batik-motifs), contains 142 images of the three batik motifs. These images are used for training and testing the deep learning model.

## Approach
I started by preprocessing the images and performing data augmentation to enhance the dataset. I tested different models, including custom-built models and transfer learning techniques like MobileNetV2 and others, to see which yielded the best results in classifying the batik patterns. The models were evaluated based on their accuracy in correctly identifying the motifs.

## Results
After fine-tuning the MobileNetV2 model, I achieved an accuracy of 93.75% on the test set. This model performed well at recognizing the motifs, even in images of people wearing batik. To improve the model's performance further, I recommend expanding the dataset to include a wider variety of batik patterns and conditions. This would enhance the model's reliability and usefulness in real-world applications, ultimately contributing to the preservation of Indonesia's rich cultural heritage.
