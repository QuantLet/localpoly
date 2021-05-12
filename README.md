[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **localpoly** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of Quantlet: 'localpoly'

Published in: 'Trading Strategies for Bitcoin Options using State Price Densities (Master Thesis)'

Description: 'This package uses Local Polynomial Regression to create a fit to the data. 
The model conveniently also estimates the first and second derivative of the fit. 
A Cross Validation finds the optimal bandwdith for the fit in case it is unknown.'

Keywords: 'Local Polynomial Regression, Local Polynomial Estimation, locpol, Fit, Fitting, Taylor Expansion' 

Author: 'Franziska Wehrmann'

See also: 'https://github.com/franwe/spd_trading'

Submitted:  '11. May 2021'

Input: '2D data cloud'

Output:  'Fit and derivatives'

Additional Info: 
- Please note, this is a fork of a original package as of 2021-05-11, the original can be found here  https://github.com/franwe/localpoly
- The PyPi documentation can be found under this link https://localpoly.readthedocs.io/en/latest/'

```

# localpoly

This package uses Local Polynomial Regression to create a fit to the data. The model conveniently also estimates the first and second derivative of the fit.

The main functions are LocalPolynomialRegression.fit, which creates the fit and LocalPolynomialRegressionCV.bandwidth_cv, which finds the optimal bandwidth for the kernel which is used for the fit.

Read the documentation for the theoretical background and examples. 

## Installation

Via pip
```
    pip install localpoly
```

Or via download from git:

```
    pip install git+https://github.com/franwe/localpoly#egg=localpoly
```

Note that in order to avoid potential conflicts with other packages it is strongly recommended to use a virtual environment (venv) or a conda environment.

![See image in README.md in GitHub repo.](https://github.com/franwe/localpoly/blob/main/docs/_static/example_fit.png?raw=true)
