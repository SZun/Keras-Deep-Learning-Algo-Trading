# Keras-Deep-Learning-Algo-Trading
Multiple algorithmic trading strategies leveraging Keras for deep learning and the OANDA and FXCM trading APIs

## [Notebook Here](https://github.com/SZun/Keras-Deep-Learning-Algo-Trading/blob/main/Keras-Algo-Trading.ipynb)

## Images from Notebook

![](./assets/DNN1.png)
![](./assets/DNN2.png)
![](./assets/DNN3.png)

## Getting Started

### Prerequisites

You must have anaconda and conda installed

```
$ anaconda --version
```
*# OUTPUT: "anaconda Command line client (version 1.11.0)"*
```
$ conda --verison
```
*# OUTPUT: "conda 22.9.0"*


### Installing

**Clone** the repo using SSH

```
$ git clone git@github.com:SZun/Keras-Deep-Learning-Algo-Trading
```

Then **cd** into the directory

```
$ cd Keras-Deep-Learning-Algo-Trading
```

Create the environment, add it to jupyter and launch jupyter lab

```
$ conda env create -f algotrading_env.yml
$ conda activate algotradingenv
$ pip install --upgrade git+https://github.com/yhilpisch/tpqoa.git
$ conda deactivate
$ jupyter kernelspec remove ENVIRONMENT_1_NAME ENVIRONMENT_2_NAME
$ conda install -c conda-forge nb_conda_kernels -y
$ jupyter lab
```

## Built With

- [Keras](https://keras.io/)
- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/docs/#)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [Fxcmpy](https://fxcmpy.tpq.io/00_quick_start.html)
- [Tpqoa](https://github.com/yhilpisch/tpqoa)
- [Pickle](https://docs.python.org/3/library/pickle.html)
- [Datetime](https://docs.python.org/3/library/datetime.html)
- [Time](https://docs.python.org/3/library/time.html)

## Author

**Samuel Zun** 
- [LinkedIn](https://www.linkedin.com/in/szun/) | [Github](https://github.com/SZun)