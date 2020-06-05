# A Contemporary Analysis on the Empirical Performance of Equity Premium Prediction

Equity investors hold the belief that certain fundamental ratios or economic factors can predict equity premium, with a plethora of literature attesting for any and every predictor imaginable. 

Through re-examining the methods proposed by *Welch & Goyal (2008)*, *Rapach et al. (2009)* and *Fabian & Lukas (2016)* using recent data up to December 2018, we confirm the results from previous studies and found structural instabilities in well documented economic and technical variables. 

Grounded on economic reasoning proposed by literature, we extended the literature by employing machine learning techniques to enhance our predictive regression framework: Regularized Regressions (**Ridge** and **Lasso**) and **Artificial Neural Networks**. These methodologies yield more stable models and better Out-of-Sample performances than traditional econometrics models over the same period.

## Installations

```
pip3 install -r requirements.txt
```
* matplotlib
* pandas
* numpy
* tqdm
* statsmodels
* scipy
* scikit-learn
* cntk
* pickle
* Keras
* ipython

## Files Description

### *Intro - A Contemporary Analysis on the Empirical Performance of Equity Premium Prediction.pdf*

A summary of our paper which details our research question, a review of the existing literature, our methodology, and our main findings and limitations. The full paper may be available upon request from the author.

### *PredictorData2018.xlsx*

A dataset spanning from January 1950 to December 2018 with monthly US equity index returns, a range of fundamental economic indicators, monthly US risk free rates, and monthly US equity index trading volumes (and On Balance Volume). Much of the data can be found on Professor *Amit Goyal's* [website](http://www.hec.unil.ch/agoyal/), and data on trading volumes are gathered from Yahoo Finance.

### *Equity-Premium-Prediction.ipynb*

All data preprocessing, modelling, and evalution are contained within this Jupyter notebook. 

## Licensing, Authors, and Acknowledgements

Some of the code are from Professor *Raymond Kan* at *The University of Toronto*. 

[MIT License](https://github.com/jasonho0810/equity-premium-prediction/blob/master/LICENSE)