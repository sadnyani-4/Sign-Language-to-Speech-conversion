Sign to Speech Conversion using Convolutional Neural Network


This project aims to convert sign language gestures into spoken language using convolutional neural networks (CNNs).

Introduction
Sign language is an important mode of communication for people who are deaf or hard of hearing. However, it can be challenging for those who need to learn sign language to understand or communicate with individuals who use it. This project addresses this challenge by using machine learning to translate sign language gestures into spoken language automatically.

Dependencies
This project requires the following dependencies:
1. Python 3.x
2. TensorFlow 2.x
3. OpenCV 4.x

Usage
To use this project, follow these steps:
1. Install the required dependencies.
2. Run the “ASL.ipynb” Jupyter Notebook file to train the CNN model on the provided dataset of sign language gestures.
3. Run the “Project Stage - 2.ipynb” Jupyter Notebook file to execute the sign-to-speech conversion using the trained CNN model.
4. Run the “image augment.ipynb” Jupyter Notebook file to generate additional training data by applying image augmentation techniques to the original dataset.

Dataset
The dataset used in this project is the American Sign Language (ASL) dataset, which contains over 27,000 images of hand gestures representing the 26 English alphabet letters. The dataset is preprocessed and split into training and testing sets before being fed into the CNN model.
The dataset used in this project also consists of five words in American Sign Language (ASL): "hello," "sorry," "yes," "iloveyou," and "thanks." Each word has a dataset of 360 images, which were created using image augmentation techniques such as rotation, translation, and flipping. The dataset is preprocessed and split into training and testing sets before being fed into the CNN model.

CNN Model
The CNN model used in this project consists of multiple convolutional and pooling layers, followed by fully connected layers for classification. The model is trained on the ASL dataset and achieves an accuracy of over 98% on the testing set.

Results
The Sign to Speech conversion using CNNs has achieved promising results, with an accuracy of over 90% on the provided test data. However, the model may not perform as well on sign language gestures not included in the training dataset.

Contact
If you have any questions or feedback about this project, please contact me at sadnyanig@gmail.com.