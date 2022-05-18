# Meme impact on volatility across markets

We are looking to evaluate the relationship between Social Commentary data and stock/cryptocurrency price motion. Here we are using the ‘mentions’ data to establish a high level view of this relationship and then proceed to further comb out that correlation in other coins. We will evaluate the relationship between mentions and price motion as is pertinent to the scope of this project and this interface with liimited acceess to data allows. 

## Technologies

This project leverages Python 3.9.7 ((default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32) with the following packages:
 
* [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/user/urls.html#managing-workspaces-ui) - For information about the jupyter lab remote workspace hosted by a local computer.
 
* [pandas](https://pandas.pydata.org/docs/) - Source repository. 
pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

* [hvplot.pandas](https://hvplot.holoviz.org/) pandas
The PyData ecosystem has a number of core Python data containers that allow users to work with a wide array of datatypes

* [pathlib](https://docs.python.org/3/library/pathlib.html#module-pathlib) - For the command line interface, help page, and entry-point.

* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - Source repository.
Alpaca offers simple, modern API-first solutions to enable anyone, either individuals or businesses, to connect applications and build algorithms to buy and sell stocks or crypto.

* [dotenv](https://pypi.org/project/python-dotenv/) - Read key-value pairs from a .env file and set them as environment variables
Python-dotenv reads key-value pairs from a .env file and can set them as environment variables. It helps in the development of applications following the 12-factor principles.

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import requests
import os
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
import hvplot.pandas
```

---

## Usage

Use the social_meme_impact.ipynb notebook to evaluate the last 24 hour period in order to compare the five leading stocks and cryptocurrencies price motion against the meme 'mentions' activity from apewisdom API .



---

## Contributors

Team Members:
Richie Martinez
Abhi Banerjee
Brian Kim
Gerald Cortright
Jennifer Jackson

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
