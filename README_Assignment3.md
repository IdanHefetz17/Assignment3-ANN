
# Assignment 3 - Artificial Neural Network Implementation

This repository contains the solution for Exercise 3, which focuses on implementing and extending a multi-layer artificial neural network as described in Chapter 11 of the book *"Machine Learning with PyTorch and Scikit-Learn"* by Sebastian Raschka et al. (2022).

## Project Overview
- Extend the original notebook to include **two hidden layers** instead of one.
- Train and evaluate the network on the **MNIST dataset**, using a **Train (70%) / Test (30%)** validation split.
- Compare the performance of the modified network with:
  1. The original single-hidden-layer implementation.
  2. An alternative implementation using **TensorFlow**.

## Repository Contents
1. **Original Chapter 11 Notebook**  
   [Original Notebook](https://github.com/rasbt/machine-learning-book/blob/main/ch11/ch11.ipynb)

2. **Modified Chapter 11 Notebook**  
   [Modified Notebook](https://github.com/IdanHefetz17/Assignment3-ANN/blob/main/modified_ch11.ipynb)

3. **TensorFlow Implementation**  
   [TensorFlow Notebook](https://github.com/IdanHefetz17/Assignment3-ANN/blob/main/Tensorflow_implementiation_of_ANN.ipynb)

4. **Python Code for Modified Notebook**  
   [Modified Python File](https://github.com/IdanHefetz17/Assignment3-ANN/blob/main/modified_ch11.py)

5. **Python Code for TensorFlow Implementation**  
   [TensorFlow Python File](https://github.com/IdanHefetz17/Assignment3-ANN/blob/main/Tensorflow_implementiation_of_ANN.py)

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/IdanHefetz17/Assignment3-ANN.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the relevant notebook or Python file in your environment (e.g., Jupyter Notebook, PyCharm).

## Results
- Performance metrics (macro AUC, accuracy, etc.) are available in the PDF included with this repository.
- Comparisons between the different implementations highlight the effectiveness of the two-hidden-layer network.

## Author
Idan Hefetz
