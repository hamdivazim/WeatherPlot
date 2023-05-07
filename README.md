# WeatherPlot
A Jupyter Notebook that can plot rain predictions using matplotlib and open-meteo.

<img src="https://github.com/hamdivazim/WeatherPlot/raw/main/screenshot.png">

## Prerequisites
You will need:
* `geopy`
* `requests`
* `pandas`
* `matplotlib`
* `seaborn`
* IPYNB Kernel

These are all in `requirements.txt`.

## How to run
Simply run all cells. There will be an input prompt asking for which city you want rain prediction data for, then at the bottom of the notebook it will generate 2 line graphs, one for predicted amount of rainfall (mm) and one for rain probability (%) for the whole day. The already generated graphs were made with this geodata:
```
[["2023-05-06T00:00 to 2023-05-06T23:00"], ["latitude": 51.5, "longitude": -0.120000124], ["London"]]
```

## How it works
Using https://open-meteo.com, this notebook gets hourly rain prediction data and converts the data into a `pandas.DataFrame`. This DataFrame is then used to generate graphs.

## Contributions?
Maybe you could open a pull request and add more graphs?

## License
WeatherPlot is licensed by Hamd Waseem under [the Apache License 2.0](https://github.com/hamdivazim/WeatherPlot/blob/main/LICENSE).
