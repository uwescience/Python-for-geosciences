## 2019-04-02. Rivers and watersheds: Hacking on packages, API's and datasets for river network and watershed characterization

**[Emilio Mayorga](https://github.com/emiliom/), UW Applied Physics Laboratory**

Following up on last week's [WaterHackWeek](https://waterhackweek.github.io/) and other recent work, join me to hack on open source Python packages, web-service API's and datasets for carrying out commonly needed data pre-processing and analysis tasks. These include digital terrain analysis, river network extraction and connectivity analysis, watershed delineation, watershed characterization, and others, for any application -- hydrological, ecological, water quality and biogeochemistry, etc.

We can examine some tools and datasets together, break up into small groups to figure out how to use these tools, compare performance, help document some of those tools, or develop some Jupyter notebooks to share with others.

I've started a document listing and grouping some of the tools and datasets I've looked into or am interested in examining:
https://github.com/emiliom/uwfreshwater_em/blob/master/RiverNetworksWatersheds_Tools.md
I'll add more information to this document by Tuesday, including links to Jupyter notebooks.

Tools we'll consider and their underlying packages include HydroShare, TauDEM, Landlab, pysheds, NLDI (hydro Network-Linked Data Index), anytree, GeoPandas and rasterio. Datasets may include global datasets (HydroSHEDS, HydroBASINS, STN-30p), national US datasets (HUCs, WBD, NHDplus), regional datasets (e.g., ArcticDEM) or high-resolution local datasets.

I've created a [conda environment file that includes most of these packages](https://github.com/uwescience/Python-for-geosciences/blob/master/20190402/environment.yml). Download it, then create the environment with `conda env create -f environment.yml`.


### Examples I'll start out with

1. **ModelMyWatershed.** Web appication demo, delineating US watersheds big and small. TauDEM + RWD in the backend. [https://modelmywatershed.org](https://modelmywatershed.org/). And corresponding [web service API jupyter notebook example](http://nbviewer.jupyter.org/github/WikiWatershed/model-my-watershed/blob/develop/doc/MMW_API_watershed_demo.ipynb).
2. **NLDI, Hydro Network-Linked Data Index.** [https://owi.usgs.gov/blog/nldi-intro/](https://owi.usgs.gov/blog/nldi-intro/)
3. **GeoHackWeek Vector Advanced tutorial, HydroBASINS example.** [HydroBASINS watersheds jupyter notebook illustrating pfastetter watershed code querying and use, plus `rasterstats` polygon-on-raster zonal statistics](https://nbviewer.jupyter.org/github/geohackweek/tutorial_contents/blob/master/vector/notebooks/geopandas_advanced.ipynb)
4. **WaterHackWeek pysheds example.** See [here](https://github.com/waterhackweek/whw2019_AndeanAmazonHydro/blob/master/WatershedExtractionAndProperties_pysheds_Emilio.ipynb) (AND ADD TO IT NOW FROM THE DEVELOPER'S EXAMPLE OF MULTI-WATERSHEDS!)
5. My Costa Rica proposal notebook, HydroBasin watershed properties and tabular compilation
6. `anytree` CR example?
