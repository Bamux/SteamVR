# Steam VR Statistics
This project analyses all Steam VR only games and determines the daily number of players since 2016. The required information was obtained from https://store.steampowered.com and https://steamdb.info with [Python](https://www.python.org/ "Python") using the [Requests](https://requests.readthedocs.io/en/master/# "Requests"), [JSON](https://docs.python.org/3/library/json.html "JSON") and [lxml](https://lxml.de/ "lxml") library. The information is stored in a [SQLite](https://www.sqlite.org/index.html "SQLite") database and evaluated with [Matplotlib](https://matplotlib.org/3.1.1/index.html# "Matplotlib") and [Seaborn](https://seaborn.pydata.org/# "Seaborn"). The database I have created with over 1.7 million records is available to everyone and can be used for all kinds of statistics and forecasts.
<img src="/images/top10.png" width="850" height="500">
<img src="/images/avg_peak_over_time.png" width="850" height="500">
<img src="/images/top10_max_peak.png" width="850" height="500">
<img src="/images/monthly_vrusage.png" width="850" height="500">
<img src="/images/max_peak.png" width="850" height="500">