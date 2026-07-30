
# Experiment 2 – Multi-Layer Perceptron (MLP) for Multi-Class Image Classification

## Objective
Implement a Multi-Layer Perceptron (MLP) using TensorFlow/Keras on the Fashion-MNIST dataset for multi-class image classification. The experiment also includes automated hyperparameter optimization using RandomizedSearchCV and an implementation of the XOR gate using an MLP.

## Dataset
- **Dataset:** Fashion-MNIST
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28
- **Number of Classes:** 10

## Model Architecture
### Baseline MLP
- Input Layer: 784 neurons
- Hidden Layer 1: Dense(128), ReLU
- Hidden Layer 2: Dense(64), ReLU
- Output Layer: Dense(10), Softmax

### Optimized MLP
- Hidden Layers: 1
- Hidden Neurons: 256
- Activation: Tanh
- Optimizer: Adam
- Learning Rate: 0.001
- Batch Size: 64
- Epochs: 20
- Dropout: 0.2

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

## Hyperparameter Optimization
RandomizedSearchCV with SciKeras was used to search for the best hyperparameters using 5-fold cross-validation.

## XOR Gate using MLP
A Multi-Layer Perceptron was implemented for the XOR gate to demonstrate that XOR is not linearly separable and cannot be solved using a single-layer perceptron.

## Repository Contents
```

```
Experiment_2/
│── Experiment_2.ipynb
│── Experiment_2_Report.pdf
│── README.md
│── requirements.txt
└── figures/
```

```markdown
## Libraries Used
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciKeras

## References
- TensorFlow Documentation
- Fashion-MNIST Dataset
- Goodfellow et al., Deep Learning
- Bishop, Pattern Recognition and Machine Learning
- Haykin, Neural Networks and Learning Machines
