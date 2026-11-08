# Handwritten Digit Classification using TensorFlow

## Project Overview
This project implements a handwritten digit classification model using **Python, TensorFlow, and Keras**. The model is trained on the MNIST dataset to recognize handwritten digits from 0 to 9.

The project demonstrates the fundamental concepts of deep learning, including data preprocessing, neural network architecture, model training, and making predictions.

## Dataset
The project uses the **MNIST dataset**, which contains:
- 60,000 training images.
- 10,000 testing images.
- 28 × 28 pixel grayscale images.
- 10 digit classes (0–9).

The dataset is loaded directly using TensorFlow Keras.

## Technologies & Libraries
- Python
- TensorFlow
- Keras
- NumPy
- Jupyter Notebook

## Model Architecture
The model is built using the Keras Sequential API.

The architecture consists of:

1. **Flatten Layer:** Converts the 28 × 28 image into a one-dimensional array.
2. **Dense Layer:** Contains 60 neurons with ReLU activation.
3. **Output Layer:** Contains 10 neurons, representing digits from 0 to 9.

The model uses:
- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy (from logits)
- **Evaluation Metric:** Accuracy
- **Training Epochs:** 4

## Data Preprocessing
The following preprocessing steps are performed:
- Normalize pixel values by dividing by 255.
- Reshape images to include a channel dimension.
- Convert image data into float32 format.

## Installation & Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/digit-classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd digit-classification
   ```

3. Install the required libraries:

   ```bash
   pip install tensorflow numpy notebook
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Digit_Classification_model.ipynb` and run the cells sequentially.

## Model Training
The neural network is trained using the MNIST training dataset for 4 epochs.

After training, the model is saved as:

`my_mnist_model.h5`

## Making Predictions
The trained model predicts handwritten digits from the test dataset.

The notebook uses `np.argmax()` to identify the digit with the highest predicted score.

## Project Structure

```text
Digit-Classification/
│
├── Digit_Classification_model.ipynb
├── README.md
└── my_mnist_model.h5   # Generated after training
```

## Learning Outcomes
- Understanding the MNIST dataset.
- Performing image preprocessing and normalization.
- Building a neural network using TensorFlow and Keras.
- Training a deep learning classification model.
- Saving trained models.
- Making predictions using a trained model.

## Future Improvements
- Train the model for more epochs.
- Evaluate performance on the complete test dataset.
- Experiment with different neural network architectures.
- Implement a Convolutional Neural Network (CNN).
- Build a simple interface for uploading handwritten digit images.

---

**Author:** Mujeeb Ullah

**Project:** Handwritten Digit Classification using TensorFlow


