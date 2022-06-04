# ExpandoMercado

A time series analysis and model that aims to grow MercadoLibre by identifying and mining seasonal patterns and building sales forecasts.

---

## Technologies

* **Pandas**  - A python library with advanced financial analysis tools.
* **Jupyter Lab** - An IDE used for visualization.
* **anaconda** - A python framework consisting of several tools used in financial analysis, such as Pandas and Jupyter Lab.
* **hvplot** - A set of Python visualization tools used to create compelling, and interactive visualizations.  
* **sklearn** - An open-source Python library offers algorithms and models for building machine learning applications.
* **Facebook Prophet** - open-source library for time series forecasting
---

## Installation Guide
### Prerequisites
#### Prophet
It is recommended that you create a virtual environment and install prophet.
```
conda create -n <environment name> python=3.7 anaconda
conda activate <environment name>
conda install -c conda-forge prophet
```
**note:** To use prophet, import it into your notebook using `from prophet import Prophet`
**note:** remember to deactivate your environmnent when done with `conda deactivate`

#### HVPlot
Ensure hvplot is installed in your conda environment
```
conda install hvplot
```
see [hvplot installation guide](https://github.com/conda-forge/hvplot-feedstock#:~:text=Installing%20hvplot%20from%20the%20conda-forge%20channel%20can%20be,has%20been%20enabled%2C%20hvplot%20can%20be%20installed%20with%3A) for more information.

### Start Jupyter Lab
Once your conda virtural environment is started with all prerequisites, start Jupyter Lab:
```
jupyter lab
```

---

## Usage
Once Jupyter Lab has started in your browser, select the **crypto_investments.ipynb** notebook from the **Left Sidebar**.  This is the main analytical notebook.

![launch Notebook.ipynb](images/start_notebook.png)

---

## Contributors

*  **Martin Smith** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> *email:* msmith92663@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> [<img src="images/LI-In-Bug.png" alt="in" width="20"/>](https://www.linkedin.com/in/smithmartinp/)

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)