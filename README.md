# ANN/CNN Image Classification Project

## Project Description

This project uses a Convolutional Neural Network (CNN) for classroom cleanliness detection.

The model classifies images into three categories:

* Clean
* Dirty
* Moderate Dirty

## Dataset

The dataset contains classroom images divided into three classes:

* Clean
* Dirty
* Moderate Dirty

The dataset was used for training and validation of the image classification model.

## Technologies Used

* Python
* Google Colab
* TensorFlow
* Keras
* NumPy
* Matplotlib
* CNN
* Transfer Learning

## Model

The project uses a CNN-based image classification model with convolutional layers, max pooling, dense layers, dropout, and softmax classification.

Transfer learning and fine-tuning can also be used to improve validation performance.

## Training

The dataset is divided into training and validation sets.

Early Stopping is used to reduce overfitting and restore the best model weights.

## Results

The model performance is evaluated using:

* Training Accuracy
* Validation Accuracy
* Validation Loss
* Classification predictions

## How to Run

1. Open the notebook in Google Colab.
2. Upload or connect the dataset.
3. Run the cells in order.
4. Train the model.
5. Evaluate validation accuracy.
6. Upload test images and generate predictions.

## Project Structure

```text
ANN-Image-Classification/
│
├── ANN_Project.ipynb
├── README.md
├── requirements.txt
└── test_images/
```

## Conclusion

This project demonstrates how deep learning can be used to automatically classify classroom images according to their cleanliness level.
