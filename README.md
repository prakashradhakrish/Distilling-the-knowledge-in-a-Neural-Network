# Distilling-the-knowledge-in-a-Neural-Network
Reproducibility of paper 

## Repository contain following models:
- Teacher model - 2 layers of 1200 units
- Student model - 2 layers of 800 units
- Student model - 2 layers of 300 units
- Student model - 2 layers of 30 units

## Dataset used:
- MNIST - jittered by 2 pixel
- Modified MNIST(transfer set) - class 3 removed in training set

## Code helps to understand:
- basics of knowledge distillation
- power of knowledge distillation with tranferset
- setting temperature hyperparameters based on the number of units in the hidden layer

## For complete explanation check: https://medium.com/@arvindwaskarthik/6f469066be7e
