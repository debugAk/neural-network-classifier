Neural Network

This project implements a **two-layer neural network from scratch** (NumPy only) to classify simple binary images of the letters **A, B, C**.

 Contents
- Dataset: 5×6 binary patterns for A, B, C
- Data augmentation: Random pixel flips to improve robustness
- Neural network:
  - Hidden layer with Sigmoid activation
  - Output layer with Softmax activation
  - Loss: Cross-entropy
  - Optimizer: Mini-batch gradient descent (backpropagation)
- Training: Shows decreasing loss and increasing accuracy
- Results: Predictions on canonical and noisy letter samples

 How to Run
1. Install requirements:
   ```bash
   pip install numpy matplotlib
   ```
2. Open `Assignment7_NeuralNetwork.ipynb` in Jupyter or VS Code.
3. Run the notebook cell by cell to train the network and view results.

 Files
- `Assignment7_NeuralNetwork.ipynb` — Jupyter notebook with full code and plots
- `Assignment7_Description.docx` — Short writeup/description
- `README.md` — This file

 Conclusion
The trained neural network successfully learns to classify letters **A, B, and C** with high accuracy, demonstrating the principles of feedforward networks, backpropagation, and classification.

