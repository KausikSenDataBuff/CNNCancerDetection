## Histopathological Cancer Cell Detection with CNNs

This repository explores the use of Convolutional Neural Networks (CNNs) for histopathological cancer cell detection. It compares the performance of a base CNN model and a VGG16 model pre-trained with ImageNet weights.

### Getting Started

**Prerequisites:**

* Python (>=3.6)
* TensorFlow
* Keras

**Installation:**

1. Clone this repository:

```bash
git clone https://github.com/<your_username>/histopathology_cancer_detection.git
```

2. Install required libraries:

```bash
pip install -r requirements.txt
```

### Running the Notebooks

This repository contains Jupyter Notebooks for training and evaluating the CNN models:

* `base_cnn.ipynb`: Trains and evaluates a base CNN model.
* `vgg16_transfer_learning.ipynb`: Performs transfer learning with a pre-trained VGG16 model.

To run the notebooks:

1. Open a terminal in the project directory.
2. Start a Jupyter notebook server:

```bash
jupyter notebook
```

3. Open the desired notebook (e.g., `base_cnn.ipynb`) from the browser window that opens.

**Note:** These notebooks require modifying file paths and potentially adjusting hyperparameters to match your specific data and environment.



### Future Work

This project serves as a starting point for further exploration. Here are some potential future directions:

* Hyperparameter tuning of the base CNN model.
* Data augmentation techniques to improve model generalizability.
* Fine-tuning the VGG16 model for histopathological cancer cell detection.
* Exploring more advanced CNN architectures for medical image analysis.


### Contributing

We welcome contributions to this project. Feel free to fork the repository and submit pull requests with your improvements.
