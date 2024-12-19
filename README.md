# MathDNN: Deep Neural Networks for Large Number Addition

MathDNN is an experimental project exploring the capabilities and limitations of Deep Neural Networks (DNNs) in performing numerical addition, with a particular focus on handling numbers outside the training range. This project investigates various techniques to improve the model's performance and generalization abilities.

## Project Overview

While addition is a simple mathematical operation, teaching neural networks to perform accurate addition on numbers significantly larger than those in their training set presents interesting challenges. This project systematically explores these challenges and implements various solutions to improve the model's performance.

## Setup Instructions

- Clone the repository and navigate to it:
   ```bash
   git clone https://github.com/kumarsandeep567/mathdnn.git

   cd mathdnn
   ```

- Please install the dependencies by running 
   ```bash
   pip install -r requirements.txt
   ```

- **Installing TensorFlow** : To ensure you install the correct version of TensorFlow, please refer to TensorFlow's official installation guide [here](https://www.tensorflow.org/install/pip)

## Key Features

- Implementation of a basic DNN for numerical addition
- Systematic analysis of model limitations with large numbers
- Implementation and evaluation of five distinct improvement strategies
- Comprehensive performance comparisons across different approaches

## Techniques Explored

1. **Data Range Expansion**
   - Widening the training data range
   - Testing model performance on increasingly large numbers

2. **Feature Scaling**
   - Implementation of MinMaxScaler
   - Normalization of input data for better model performance

3. **Architecture Enhancement**
   - Increased model complexity
   - Additional layers and neurons
   - Performance analysis of deeper architectures

4. **Regularization**
   - L2 regularization implementation
   - Prevention of overfitting
   - Improved model generalization

5. **Logarithmic Transformation**
   - Alternative data representation
   - Analysis of transformation effects on model performance

## Results

- Feature scaling and increased model complexity proved most effective
- Regular models showed accuracy around 12% for out-of-range numbers
- Enhanced models achieved percentage errors below 0.0002%
- Logarithmic transformation showed limited effectiveness for addition tasks

## Key Findings

- Neural networks can be effectively trained to perform addition on numbers significantly larger than those in their training set
- Proper data preprocessing and model architecture are crucial for handling large numbers
- Feature scaling is essential for consistent performance across different number ranges
- Model complexity needs to be balanced with regularization for optimal results

## Future Work

- Investigation of alternative network architectures
- Exploration of different preprocessing techniques
- Extension to other mathematical operations
- Performance optimization for even larger numbers

