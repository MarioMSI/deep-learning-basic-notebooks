# MNIST Classification with Convolutional Neural Networks

## ABOUT MNIST
The MNIST dataset is a large database of handwritten digits that is commonly used for training various image processing systems. The dataset contains 60,000 training images and 10,000 testing images. Each image is a 28x28 grayscale image representing a digit from 0 to 9.

## DESCRIPTION
This project involves the classification of handwritten digits using Convolutional Neural Networks (CNNs) implemented with TensorFlow and Keras. The work includes:

- Developing a Sequential model to classify the MNIST dataset.
- Exploring different model architectures to improve classification accuracy.
- Comparing model performance using both the MNIST dataset and custom-generated data.
- Inference pipeline.

### Key Steps in the Notebook:
1. **Data Preprocessing**: Loading and preprocessing the MNIST dataset.
2. **Model Development**: Creating and training different CNN architectures using the Sequential API.
3. **Evaluation**: Evaluating model performance using various metrics.
4. **Custom Data Generation**: Generating custom handwritten digit images for additional testing.
5. **Inference pipeline**: Comparing the model's performance on the original MNIST data and the custom-generated data. 

The notebook provides detailed code and explanations for each step, offering insights into the model development process and the impact of different architectural choices on classification performance.

### How to Use This Notebook
1. Clone this repository.
2. Run the Jupyter Notebook to see the results and visualizations.

### Dependencies
Check requirements.txt file
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn