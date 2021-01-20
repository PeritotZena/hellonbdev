# Finance
> Analysing portfolio's with python & WB data


This file will become your README and also the index of your documentation.

First you need to clone the repository. Use git clone.

## Install

`pip install finance`

## How to use

Just trying out some stuff here for the documentation

```python
1+1
```




    2



Calculating log returns of prices

```python
def log_return(prices):
  np.log(prices / prices.shift(1))
```
