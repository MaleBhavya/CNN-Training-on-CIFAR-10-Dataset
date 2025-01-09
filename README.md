CNN Training on CIFAR-10

This project implements a Convolutional Neural Network (CNN) using PyTorch for classifying CIFAR-10 dataset images. The model supports two architectures with configurable parameters.

Features
Two Architectures:
Type 1: 3 convolutional layers + 3 fully connected layers.
Type 2: 4 convolutional layers + 3 fully connected layers.
Hyperparameters: Configurable learning rate, batch size, and epochs.
Evaluation: Displays loss and accuracy for both training and testing.
GPU/CPU Support: Automatically uses GPU if available.

Requirements
Install required libraries:
pip install torch torchvision numpy matplotlib

Usage
Interactive Mode (e.g., Jupyter): Update the Config class with desired values and run the script.

Command Line: Run the script with arguments:
python PA4.ipynb --architecture_type 1 --learning_rate 0.1 --batch_size 100 --epochs 30

Output
Generates training/testing loss and accuracy plots (loss_plot.png, accuracy_plot.png). Best test accuracy is printed in the console.

The project downloads the CIFAR-10 dataset automatically during execution.






