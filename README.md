# San Fransisco Housing Proptech Picture

This is a Jupyter Notebook that uses hvplot to help a company make financial decestions. We are looking over the units for rent and sale in San Fransisco from 2010 to 2016. We break down the price per square foot anf gross rent for each neighborhood. Lastly this notebook creates visuals to show each neighborhood on a map to help with those decesions to buy and rent.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [hvplot](https://github.com/holoviz/hvplot) - A high-level plotting API for pandas, dask, xarray, and networkx built on HoloViews

* [metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
```


---

## Usage

Acitvate a Jupyter Lab Notebook by having the kernal installed and typing `jupyter lab` in your terminal. 

User mush have the 'MCForcastTools.py' moduel in order to run the simulation.

---

## Examples

```
housing_units_by_year.hvplot.bar(ylim=(365000,385000),x="year",
                                 y="housing_units",
                                rot=90,
                                color = "blue",
                                title = "Housing Units in SF 2010 to 2016").opts(yformatter='%.0f')
```

---

## Contributors

DU Starter Code
Terrence McCoy


---

## License

MIT
