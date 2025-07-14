# Codetech-Task-2

Name:- BISHAL KUMAR SHARMA 
Company:- CODETECH IT SOLUTIONS 
Domain:- DATA SCIENCE 
ID:-CT04DG1321
Duration:- 14th JUNE to 14th JULY 2025
Mentor:- NEELA SANTOSH KUMAR 


# MNIST Image Classification with CNN (TensorFlow)

This repository contains a Python script that trains a **Convolutional Neural Network (CNN)** using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

It also visualizes training & validation accuracy and loss and saves the trained model to disk.

---

## Features

- Loads & preprocesses the MNIST dataset  
- Builds a CNN model for image classification  
- Trains the model and evaluates test accuracy  
- Visualizes training & validation performance  
- Saves the trained model as `.h5`

---

## Getting Started
### Prerequisites

- Python 3.7+
- Recommended to use a virtual environment
- Install the required libraries:
```bash
pip install tensorflow matplotlib numpy
```

---

## Running the Script

Run the script from terminal:
```bash
python image_classification.py
```

---

## Output
When you run the script:
- Trains the CNN model on MNIST dataset.
- Prints model architecture and final test accuracy.
- Shows plots of training/validation accuracy and loss.
- Saves trained model as:
  ```
  mnist_cnn_model.h5
  ```

Example final test accuracy:
```
Final Test Accuracy: 0.9854
```

---

## Repository Structure

```
- your-repo/
- image_classification.py      # Main script
- README.md                    # Documentation
- mnist_cnn_model.h5           # (Generated) Trained Model
```

---

## Notes

- The model trains for **5 epochs** by default : you can adjust the `epochs` parameter in the script.
- You can also experiment with deeper architectures or different optimizers for better accuracy.
- The MNIST dataset is downloaded automatically by TensorFlow when running the script.

---

## Technologies Used

- [TensorFlow](https://www.tensorflow.org/) : Deep learning library.
- [Keras](https://keras.io/) : High-level API for TensorFlow.
- [Matplotlib](https://matplotlib.org/) : Visualization library.
- [NumPy](https://numpy.org/) : Numerical computing.

---

## Resources
- YouTube
- Chatgpt
- Google 
