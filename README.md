# Meme impact on volatility across markets
-

We are looking to evaluate the relationship between Social Commentary data and cryptocurrency price motion. We will initially be using the ‘mentions’ data to establish a high level view of this relationship and then proceed to further comb out that correlation in other coins. We will evaluate the relationship between mentions and price motion in ten coins and ten meme stocks.

## Technologies

This project leverages Python 3.9.7 ((default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32) with the following packages:
 
* [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/user/urls.html#managing-workspaces-ui) - For information about the jupyter lab remote workspace hosted by a local computer.
 
* [pandas](https://pandas.pydata.org/docs/) - Source repository. 
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [hvplot.pandas](https://hvplot.holoviz.org/) pandas
The PyData ecosystem has a number of core Python data containers that allow users to work with a wide array of datatypes

* [pathlib](https://docs.python.org/3/library/pathlib.html#module-pathlib) - For the command line interface, help page, and entry-point.

* [geopandas](https://geopandas.org/en/stable/)
GeoPandas is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by pandas to allow spatial operations on geometric types. Geometric operations are performed by shapely. Geopandas further depends on fiona for file access and matplotlib for plotting.
---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
import geopandas as gpd
```

---

## Usage

Use the san_francisco_housing.ipynb notebook to visualize and analyze the real-estate data.

Create a visualization by using hvPlot and GeoViews. Additionally, you need to read the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook and create the DataFrame that you’ll use in the analysis.

Use the san_francisco_housing.ipynb notebook to complete the following tasks:

    Calculate and plot the housing units per year.

    Calculate and plot the average prices per square foot.

    Compare the average prices by neighborhood.

    Build an interactive neighborhood map.

    Compose your data story.



---

## Contributors

Gerald Cortright and Berkeley Fintech support staff
---

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
