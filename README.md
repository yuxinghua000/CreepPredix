# MLND
## Capstone Project: Evaluation of Regression Models for Creep Prediction of CrMo Steels

### Requirements

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)



### Code

Code is provided in the `creep.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `creep_5.csv` dataset file to complete.



## Data

The creep data is included as a selection of 2060 data points from (https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
Chemical composition - 

C, Si, Mn, P, S, Ni, Cr, Mo, W, Cu, V, Nb, N, Al, O (all in wt. %)

minor alloy elements were omitted.

Heat treatment conditions - 

N_T      normaling temperature
N_Time   normaling time
T_T      tempering temperature
T_Time   tempering time

Creep testing conditions – 

stress and temperature

**Target**

Larson Miller Parameter -

LMP = T*(log10(t)+33)
t creep life in seconds
T testing temeprature in Kelvin
