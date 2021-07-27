# Linear Regression



## Task

There exists a function ![image](http://latex.codecogs.com/gif.latex?f%3A%20%5Cmathbb%7BR%7D%5Crightarrow%20%5Cmathbb%7BR%7D) , 
about which ![image](http://latex.codecogs.com/gif.latex?y%20%3D%20f%28x%29) we don't have any knowledge.

Given a dataset ![image](http://latex.codecogs.com/gif.latex?%5Cleft%20%5C%7B%20%5Cleft%20%28%20x_%7B1%7D%2Cy_%7B1%7D%20%5Cright%20%29%2C...%2C%5Cleft%20%28%20x_%7BN%7D%2Cy_%7BN%7D%20%5Cright%20%29%20%5Cright%20%5C%7D%2CN%3D300) 
for training, Use *Linear Regression* to fit the function <img src="https://render.githubusercontent.com/render/math?math=y=f(x)"> .

(It is recommended to try a variety of basis functions like polynomial, Gaussian, sigmoid, etc.)


## Dataset 

`train` and `test` set generated according to some certain function.


## Finished Exercise
- `TODO` in [exercise-linear_regression.ipynb](./exercise-linear_regression.ipynb) <br>
  1. *Optimization* through <br>
     1. Least Square Method (LSM); <br>
     2. Gradient Descent. <br>
  2. *Basis Function* <br>
     1. Polynomial; <br>
     2. Gaussian. <br>
  
- Using `pytorch`, finish  [linear_regression-pytorch.ipynb](./linear_regression-pytorch.ipynb) ,<br>
  (referring to [linear_regression-tf2.0.ipnb](./linear_regression-tf2.0.ipynb) ).
  
- Note: Training the model on `train.txt` and evaluate it on `test.txt` through *Standard Deviation*.
