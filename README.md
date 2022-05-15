# Nottingahm-Economics-Dissertation
BSc Economics Dissertation UON: GDP forecasting model comparison code.

To use this code depoendencies must be installed by installing all packages in requirements.txt via pip.

Then import the package into a notebook and run the recursive estimation method as shown:

```
  from FredQD import FredQD
  fqd = FredQD()
  fqd.estimate_recursive()
```
This wll take a long time to run all the forecasts. 

Results and forecasts are stored as attribute in the fqd class. 

Get results dataframes inside lists. E.g. for a list of all MSE dataframes (in order of horizon)

```
  fqd.mse
```
