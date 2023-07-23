# Fashion MNIST CNN with Regularization and Data Augmentation

This repository contains code for building and training a Convolutional Neural Network (CNN) on the Fashion MNIST dataset using TensorFlow's Keras API. The CNN model is designed to classify 10 different fashion items.

## Dataset Loading

The Fashion MNIST dataset is loaded using TensorFlow's Keras API, providing training data, training labels, test data, and test labels. The dataset contains 60,000 training samples and 10,000 test samples, each represented as 28x28 grayscale images.

## Data Preprocessing

The images in the dataset are preprocessed by reshaping them to create an input shape for the CNN and scaling the pixel values to the range [0, 1]. The target labels are one-hot encoded, converting them into binary vectors for each class.

## CNN Model Building

The repository contains two main scripts for building and training the CNN model:

1. `FMNIST_keras_no_regularization_then_regularization.ipynb`: First, this script builds and trains the CNN model without any regularization techniques. Later, builds and trains the CNN model with L2 regularization applied to the Convolutional and Dense layers.



## Model Training - Without Regularization First and then With Regularization

To train the CNN model , run the following command:

```bash
FMNIST_keras_no_regularization_then_regularization.ipynb
```
This script will load the Fashion MNIST dataset, build the CNN model without regularization, and train the model. The training and validation accuracy will be displayed during training, and the final test accuracy will be shown after training. Later it will load the Fashion MNIST dataset, build the CNN model with L2 regularization, and train the model using data augmentation. The L2 regularization helps prevent overfitting by limiting the complexity of the model. Data augmentation is implemented using the ImageDataGenerator from Keras to increase the diversity of the training data.

The training and validation accuracy will be displayed during training, and the final test accuracy will be shown after training.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/FarzadMalik/FNIST_with_Keras_CNN_no_regularization_then_regularization.git
cd FNIST_with_Keras_CNN_no_regularization_then_regularization
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Run the CNN model 

```bash
FMNIST_keras_no_regularization_then_regularization.ipynb
```

Feel free to experiment with different regularization techniques and hyperparameters to observe their impact on the model's performance.

## Contributors

- [FarzadMalik](https://github.com/FarzadMalik)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
