# Problem 6: From Gradient Descent to Momentum, RMSProp and Adam

Algorithms and Data Structures Examination, Group 8

Group members:
- Manas Dogra (100006131)
- Monish Chopra (100007201)
- Aaditya Dawer (100006382)
- Aditya Aditya ( 100007877)

## What is in this repository
- Problem6_Optimizers.ipynb: Jupyter Notebook with all the code
- experiment1_canyon.png, experiment1_rosenbrock.png: paths on two hills
- experiment2.png: speed test with 50,000 samples

## What the notebook does
1. Implements five optimizers (Gradient Descent / Mini-batch SGD, Momentum,
   RMSProp, Adam) and Newton's method.
2. Tests them against our hand calculations (Q1 to Q5).
3. Experiment 1: compares them on the Canyon and Rosenbrock functions.
4. Experiment 2: linear regression with N = 50,000 and d = 50.
5. Complexity table (time per step and extra memory).

## How to run
Open the notebook in Jupyter or Google Colab and choose
"Run all". Needs Python 3.10 or newer with numpy and matplotlib.
