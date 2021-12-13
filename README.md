# Forecasting_Net_Prophet
![Photo of telescope looking at stock graph](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTFbGvu65nlI3zVR7-PXURzhYq34IPe_Hk59Aj98gia_ZnsBOtHrvw3OYK2hwpjEnPpGqE&usqp=CAU)

This application analyzes Google search traffic, stock prices, and sales revenue for the MercadoLibre stock to find patterns from forecasting and providing analysis. Forecasting is done using the fbProphet algorithm.

---

## Technologies:
This program runs on Python 3.7 and utilizes the following packages:

* [Jupyter Lab](https://jupyter.org/)

* [Facebook Prophet](https://facebook.github.io/prophet/)

* [Google Colab](https://colab.research.google.com/)

* [pandas](https://pandas.pydata.org/)

* [hvplot](https://hvplot.holoviz.org/)

---
## Installation Guide:
Make sure you have all the packages installed. To make sure, run the following in your local terminal:

```
pip install jupyterlab
pip install pandas
pip install hvplot
```
If you do not want to install Facebook Prophet on to your local computer, upload the `forcasting_net_prophet.ipynb` file in [Google Colab](https://colab.research.google.com/). 

If you wish to install Facebook Prophet copy the following code in terminal:

```
pip install pystan
conda install -c conda-forge fbprophet
```

These following imports are required:

```python
import pandas as pd
from pathlib import Path
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
```

---
## Usage:
As stated in the Installation Guide, to use Google Colab click the [Link](https://colab.research.google.com/) and upload the `forcasting_net_prophet.ipynb`

For Jupyter Lab, open `forcasting_net_prophet.ipynb` and when the cells begin to run, the user will begin to see some of the following outputs:

![Screen shot of Time Series Analysis](https://user-images.githubusercontent.com/89755088/145776086-08974566-84e2-41b4-b998-fc87d694de97.png)

![Screen shot of sales predictions](https://user-images.githubusercontent.com/89755088/145776305-172f33b3-d3aa-4f22-9b6a-6adf3dcfd9c1.png)

![Screen shot of sales time series](https://user-images.githubusercontent.com/89755088/145776681-5c856f92-7b0d-4d50-91ee-e6dbcfa503bb.png)

---
## Contributors:
Code was written by Thomas Leahy, thomasleahy6@gmail.com, In conjunction with © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand.

---
## Licence:
MIT

2021 Thomas Leahy