# ENCS5343-Computer-Vision-Project

Handwriting recognition is a computer vision problem that involves a computer identifying handwritten script and transforming the text from sources such as documents or touchscreens into a machine-understandable format. The input image can be offline (from a piece of paper or a photograph) or online (from a digital source, such as touchscreens). 

Handwritten text in each language has a wide range of patterns and styles, which are influenced by factors such as age, background, native language, and mental state. Various machine learning methods, such as K-nearest neighbors (KNNs), Support Vector Machines (SVMs), transfer learning, and deep
learning techniques such as Neural Networks (NNs), have been extensively investigated in the field of automatic handwritten recognition. Convolutional Neural Networks (CNNs) have recently been used in the majority of studies.

Arabic writing is semi-cursive and written from right to left, with 28 characters in the alphabet. Because each character has multiple shapes depending on its position in the word, automatic handwritten recognition of Arabic script is more difficult than in other languages. Because of these factors, automatic handwritten recognition of Arabic script is more difficult than in other languages.

This project aims to introduce students to the challenges and techniques of Arabic Handwritten Character Recognition (AHCR) using Convolutional Neural Networks (CNNs). The project consists of four tasks.

# Task One
Build and train a custom CNN network for AHCR. 

# Task Two
Data augmentation is a powerful technique for enhancing the diversity and the size of your training data without the need for additional data collection. By applying various transformations to existing data points, you can train models that generalize better to unseen examples and improve their overall performance. Data augmentation encompasses a wide range of techniques, only a subset of which are suitable for training the AHCR system. In this task, you must select at least three data augmentation techniques that are appropriate for this project.

# Task Three
Select a CNN network from a list of well-known and published CNN architectures, such as LeNet, AlexNet, ResNet, and so on. You must make a tradeoff between accuracy and network complexity with respect to the problem and the dataset provided. Train it using the data augmentation techniques you used in Task 2.

# Task Four
Use a pre-trained CNN network on similar tasks and choose the appropriate transfer learning method to fine tune the pretrained network on the given dataset.
