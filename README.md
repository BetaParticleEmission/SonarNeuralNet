# SonarNeuralNet

## What This Project Does
A binary classification neural network built with PyTorch that classifies sonar signals 
as either mines or rocks. The model uses a feedforward neural network (MLP) trained on 
60 sonar frequency features to predict whether a detected object is a metal cylinder 
(mine) or a rock. Achieved 90% test accuracy on the UCI Sonar dataset.

## Dataset
- **Source:** UCI Machine Learning Repository
- **Name:** Connectionist Bench (Sonar, Mines vs. Rocks)
- **URL:** https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks
- **Authors:** R. Paul Gorman and Terrence J. Sejnowski
- **Samples:** 208 (111 mines, 97 rocks)
- **Features:** 60 sonar frequency response values in the range 0.0 to 1.0
