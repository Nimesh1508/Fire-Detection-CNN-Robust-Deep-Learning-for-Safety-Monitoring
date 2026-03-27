## Description:

I developed a machine learning model for fire detection by integrating two datasets and evaluating its performance with additional images. 

The process involved several key steps:​

## Dataset Preparation:

### FireNet Dataset:

​FireNet is a specialized machine learning project aimed at real-time fire detection, offering annotated datasets, trained models, and inference codes to facilitate the development of systems capable of instant fire recognition while minimizing false alerts.

The FireNet dataset is structured to enhance the training and evaluation of fire detection models. It comprises a total of 3,296 images, categorized as follows:
​

Training:

Fire Images: 1,124, 
​
Non-Fire Images: 1,301
​

Testing:

Fire Images: 593, 
​
Non-Fire Images: 278

Firenet Dataset URL: https://tinyurl.com/mw5jm5xh

### Kaggle Dataset:

Kaggle dataset contains 110 fire images and 541 non-fire images. Partition the Kaggle dataset into training and testing subsets, adhering to an 80-20 split:

Fire Images: 110

No-fire Images: 541

Kaggle Dataset URL: https://www.kaggle.com/datasets/atulyakumar98/test-dataset

## Data Splitting:

First, splitting up the Kaggle dataset into training and testing subsets to facilitate model evaluation. A typical split allocated 80% of the data for training and 20% for testing, ensuring the model learns effectively while retaining data for unbiased evaluation.

## Combining Datasets:

After splitting up the Kaggle dataset, Firenet dataset were merged with splitted kaggle dataset.

## Model Training and Evaluation:

A Convolutional Neural Network (CNN) was employed to develop a robust fire detection model. The training phase involved feeding the network with preprocessed images from the training dataset, enabling the model to learn and identify patterns indicative of fire incidents. Following training, the model's performance was evaluated using the testing dataset to assess its accuracy and ability to generalize to new, unseen data.​
