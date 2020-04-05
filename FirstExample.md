# First example in Gaussian Regression:

Imagine that you want to fit a Gaussian model to the following data (randomly created in Matlab). 
The data has 1 input variable (x, predictor) with 10 different values and 1 output value (y, response) with 10 different values. 

```
x = linspace(0.5,2.5,10)';
y = sin(10*pi.*x) ./ (2.*x)+(x-1).^4 + 1.5*rand(10,1);
```

| X  | Y |
| ------------- | ------------- |
|    0.5000  |  0.3058 |
|    0.7222  |  0.7524 |
|    0.9444  | -0.0545 |
|    1.1667  |  0.4224 |
|    1.3889  |  0.1482 |
|    1.6111  |  1.1486 |
|    1.8333  |  1.1129 |
|    2.0556  |  2.4621 |
|    2.2778  |  3.8407 |
|    2.5000  |  6.1847 |
