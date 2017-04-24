# Introduction

[OpenData.sk initiative](http://opendata.sk) is, as part of our activities, among other things monitoring number of datasets (and some other metrics) on various Open Data catalogs (see [the data harvesting script](https://github.com/hanecak/data-catalog-stats) and [collected data](https://github.com/hanecak/data_data-catalog-stats)).

This project contains basic visualization for total dataset counts.

Suggestions, bug-reports and pull-request are welcome is the [issue tracker](https://github.com/hanecak/viz-data_catalog_stats-dataset_count/issues).
 
# License

TODO

# TODO

- add LICENSE
- tip with catalog name if mouse hovers over line, possibly with also a data and value of nearest point
- selected datacatalogs in URI, to allow deep-linking and sharing of custom selections
- maybe move captions to the right, like in https://bl.ocks.org/mbostock/3884955
- ...

# DEV tips

- loading of CSV requires HTTP, you can setup a primitive server by running `python -m SimpleHTTPServer` in the directory with this project
