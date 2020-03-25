# Steam VR Statistics
This project analyses all Steam VR only games and determines the daily number of players since 2016. The required information was obtained via web scraping from https://steamdb.info (number of daily players) and www.vrlfg.net (appid of all VR games) with [Python](https://www.python.org/ "Python") using the [Requests](https://requests.readthedocs.io/en/master/# "Requests") and [JSON](https://docs.python.org/3/library/json.html "JSON") library. The information is stored in a [SQLite](https://www.sqlite.org/index.html "SQLite") database and evaluated with [Matplotlib](https://matplotlib.org/3.1.1/index.html# "Matplotlib") and [Seaborn](https://seaborn.pydata.org/# "Seaborn"). The database I have created with over 1.6 million records is available to everyone and can be used for all kinds of statistics and forecasts.
<p align="left">
  <img width="850" height="500" src="https://github.com/Bamux/Steam_VR_Statistics/blob/master/images/top10.png">
  <img width="850" height="500" src="https://github.com/Bamux/Steam_VR_Statistics/blob/master/images/avg_peak_over_time.png">
  <img width="850" height="500" src="https://github.com/Bamux/Steam_VR_Statistics/blob/master/images/max_peak.png">
  <img width="850" height="500" src="https://github.com/Bamux/Steam_VR_Statistics/blob/master/images/monthly_vrusage.png">
</p>

