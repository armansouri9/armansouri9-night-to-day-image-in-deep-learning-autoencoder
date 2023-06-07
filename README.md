# Night to Day Image in Deep Learning Autoencoder

This repository contains the code for training a deep learning autoencoder model to convert night images to day images. The model is built using the Keras library and utilizes convolutional neural networks (CNNs) for image processing.

## Repository Specifications
- Repository: [https://github.com/armansouri9/night-to-day-image-in-deep-learning-autoencoder](https://github.com/armansouri9/night-to-day-image-in-deep-learning-autoencoder)
- Language: Python
- Libraries: Keras, TensorFlow, OpenCV, Matplotlib, Scikit-Learn

## Code Description
The code consists of the following main parts:

1. Importing the required libraries
2. Mounting Google Drive (assuming this code is run in Google Colab)
3. Unzipping the dataset
4. Loading and preprocessing the training images
5. Building the autoencoder model
6. Compiling and training the model
7. Visualizing the training loss

The code performs the following steps:
- Imports the necessary libraries for image processing and deep learning.
- Mounts Google Drive to access the dataset (assuming the dataset is stored in Google Drive).
- Unzips the dataset containing night and day images.
- Loads and preprocesses the training images using OpenCV and numpy.
- Builds an autoencoder model using Keras, consisting of an encoder and a decoder.
- Compiles the model with an appropriate loss function and optimizer.
- Trains the model on the training images for a specified number of epochs.
- Visualizes the training loss using Matplotlib.

## Instructions
To run the code, follow these steps:
1. Clone or download the repository: [https://github.com/armansouri9/night-to-day-image-in-deep-learning-autoencoder](https://github.com/armansouri9/night-to-day-image-in-deep-learning-autoencoder)
2. Install the required dependencies and libraries mentioned in the code.
3. Make sure the dataset is available and adjust the paths accordingly in the code.
4. Run the code cell by cell in a Python environment, such as Google Colab or Jupyter Notebook.

Please note that the code assumes the dataset is stored in Google Drive and may need modification if the dataset is located elsewhere.

## Dataset
The dataset used for training consists of paired night and day images. The code assumes the dataset is already available and unzipped. The images are loaded and preprocessed using OpenCV.

## Results
The model is trained to convert night images to day images using an autoencoder architecture. The training loss is visualized using Matplotlib to track the model's performance during training.

Feel free to explore the code and adapt it to your own requirements!

**Note:** This repository is intended for educational purposes and serves as an example of using deep learning for image translation. The provided code may require modifications and fine-tuning to achieve optimal results on different datasets or real-world scenarios.


## License

This project is licensed under a Free License.
