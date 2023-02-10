# BYU Pathway tuition fees around the world

Tuition fees around the world presented sorted from lower to higher and in a world map.

## Prerequisites

The code uses Selenium WebDriver, you can get WebDriver for Firefox from [mozilla/geckodriver](https://github.com/mozilla/geckodriver/releases) (choose the appropriate version depending on your OS). You could also change the relevant line of code in the notebook to use a different browser, but you will still need to get WebDriver for that browser.

## Installation

It is recommended to create a virtual environment. You can do so in any way that is convenient to you, one way of doing it is using the `venv` module included in standard python:

```shell
python -m venv .byu
```

The previous command creates a virtual environment called `.byu`, you can instead call it whatever you want.

Then, you will have to activate your virtual environment:

Windows:

```shell
.byu\Scripts\activate
```

Linux or Mac:

```shell
source .byu/bin/activate
```

Once the virtual environment has been successfully created and activated, install the dependencies:

```shell
pip install -r requirements.txt
```

## Usage

The code is in a Jupyter notebook. There are many ways of runnig Jupyter notebooks; to open the file directly in your browser use:

```shell
jupyter notebook byu_pathway_tuition_by_country.ipynb
```

The notebook will by default show tuition fees as of February 9, 2023, but you can update it by going to `Cell -> Run All`.
