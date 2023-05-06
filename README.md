# WeatherPlot
A program that can plot rain predictions using matplotlib and open-meteo.

<img src="https://raw.githubusercontent.com/hamdivazim/WeatherPlot/main/screenshot.png">

## Prerequsites
You will need:
* `geopy`
* `requests`
* `pandas`
* `matplotlib`
* `seaborn`
* IPYNB Kernel

These are all in `requirements.txt`.

## How to run
Simply run all cells. There will be an input prompt asking for which city you want rain prediction data for, then at the bottom of the notebook it will generate 2 line graphs, one for predicted amount of rainfall (mm) and one for rain probability (%) for the whole day.

## How it works
Using https://open-meteo.com, this notebook gets hourly rain prediction data and converts the data into a `pandas.DataFrame`. This DataFrame is then used to generate graphs.

## Contributions?
Maybe you could open a pull request and add more graphs?