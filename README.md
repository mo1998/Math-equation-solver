# Math Equation Solver

The goal is to implement a system that able to solve mathematical equations like this using computer vision.
![test](Test.jpg)

## Dataset
[Handwritten math symbol and digit dataset](https://www.kaggle.com/datasets/clarencezhao/handwritten-math-symbol-dataset)

## Workflow Of The System
* The model is trained to recognize handwritten digits using CNN.
* Input equation image is segmented by performing dialation and finding rectangular contours.
* The segmented digits is recognized by trained model and its location is saved.
* Sort digits by its location and perform calculation.
## Used Technologies
* matplotlib
* numby
* pandas
* opencv
* sklearn
* tensorflow

## How To Train 
➡ Run handwritten-math.ipynb
## How To Use
➡ Run equation solver.ipynb
