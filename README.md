CNN for Handwritten Digit Classification (MNIST)

This project implements a Convolutional Neural Network (CNN) in TensorFlow/Keras to classify handwritten digits using the MNIST dataset.

Files

`CNN.ipynb`: Main Jupyter notebook with data loading, preprocessing, model training, and evaluation.

Dataset

 **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/)
 **Type**: 28x28 grayscale images of handwritten digits
 **Classes**: 10 (digits 0–9)

 Model Architecture

- **Input**: 28x28x1 grayscale image
- **Layers**:
  - `Conv2D(32, (3,3), activation='relu')`
  - `MaxPooling2D(2,2)`
  - `Flatten()`
  - `Dense(100, activation='relu')`
  - `Dense(10, activation='softmax')`


 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mnist-cnn-classifier.git
   cd mnist-cnn-classifier
````

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Run the `CNN.ipynb` file cell by cell.


 Evaluation Metrics

* Training accuracy and loss
* Test accuracy
* Classification results


