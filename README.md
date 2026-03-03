<h1>Image Classifier using CNN & Transfer Learning</h1>
Deep learning-based image classification project using a Convolutional Neural Network (CNN) and Transfer Learning with a pre-trained model.

<br>This project builds an Image Classification model using:
<ul><li>Convolutional Neural Network (CNN)</li>
    <li>Transfer Learning with a pretrained model</li>
    <li>Model evaluation and performance comparison</li></ul>

The model classifies animal images into 5 different species.

<h2>Technologies Used</h2>

<ul><li>PyTorch 2.10.0</li>
    <li>NumPy 2.0.2</li>
    <li>Matplotlib 1.3.0</li>
    <li>scikit-learn 1.6.1</li></ul>

<h2>Dataset Structure</h2>

    dataset/
    ├── train/
    ├── val/
    └── test/

Each folder contains 5 subfolders (one for each class).

    ├── cat/
    ├── cow/
    ├── lion/
    ├── deer/
    └── dog/

Source: <a>https://www.kaggle.com/datasets/miadul/animal-image-classification-5-species</a>

<h2>Models Used</h2>

<h4>Custom CNN</h4>
<ul><li>Convolution layers</li>
    <li>MaxPooling</li>
    <li>Dropout</li>
    <li>Fully connected layers</li></ul>

<h4>Transfer Learning Model</h4>
<ul><li>ResNet50</li></ul>

<h2>Project Workflow</h2>

<h4>Data preprocessing</h4>
<ul><li>Image resizing</li>
    <li>Normalization</li>
    <li>Data augmentation</li></ul>

<h4>Model training</h4>
<ul><li>CNN from scratch</li>
    <li>Transfer learning (freeze layers)</li></ul>

<h4>Evaluation</h4>
<ul><li>Accuracy</li>
    <li>Recall</li>
    <li>F1 Score</li>
    <li>Confusion Matrix</li></ul>







