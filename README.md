# Image-Classification
📌 Project Overview
Image classification is a fundamental problem in computer vision. This project specifically tackles the binary classification of pet images — distinguishing between dogs and cats. The model learns visual features through multiple convolutional layers and is evaluated using accuracy metrics.

📁 Dataset
The dataset consists of images labeled as dogs or cats.

It is preprocessed by:

Resizing all images to a standard size (e.g., 150x150 pixels).

Normalizing pixel values.

Splitting into training, validation, and test sets.

Augmenting images (rotation, flipping, zooming, etc.) for better generalization.

Note: This project uses the dataset from the Kaggle "Dogs vs. Cats" competition. Due to size restrictions, dataset loading is not included in the repo. Please download and place the dataset in the correct directory.

🧠 Model Architecture
Built using Keras Sequential API

Consists of:

Convolutional layers

MaxPooling layers

Dropout for regularization

Fully connected Dense layers

Binary classification output (sigmoid activation)

Optimized with Adam optimizer and binary crossentropy loss.

📊 Results
The model achieves high training and validation accuracy.

Training/validation loss and accuracy are plotted to visualize performance.

Confusion matrix and prediction examples are shown for evaluation.


kaggle dataset link: https://www.kaggle.com/datasets/salader/dogs-vs-cats
