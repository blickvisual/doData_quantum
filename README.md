# Welcome!
Here will you find some resources, data and scripts based on the presentation. Feel free to contact us!
## Credits - OpenSky Network - Licence
We exported the date from the stunning [OpenSky Network](https://opensky-network.org/). You can use the data for exploration purpose. For forther information, please consider de license! https://opensky-network.org/datasets/states/LICENSE.txt
## Preparation
### Download this repository
You can either download it by `clone or download` and `download zip` or use your prefered git client. 
### Install GeoPandas
To work with the date, we recommend to use [GeoPandas](http://geopandas.org/), a python library made for geospatial data. It's not allways easy to install, so we don't give you an exact installation documentation.

Theoretically you can install it by pip.  
`pip3 install geopandas`  
For more information, read de [install manual](http://geopandas.org/install.html) or google it.

### Install Jupyter Notebook
All examples run in a jupyter notebook. Install it with pip  
`pip3 install jupyter`

Now open the terminal/console (on Mac: `terminal` on windows `cmd`) and navigate to this repository. Start the terminal with:  
`jupyter notebook`

### Concat files
Because GitHub has a file size restriction, we had to split the data into numerous files. Lets create one big file:
Open the file [python/0 Concatenate Files.ipynb](python/0.%20Concatenate%20Files.ipynb) and run it. This will create the file `/data_generated/20180521.csv`  

###Create a sample
During development, we use a sampled file, to preserve our computer. Run the File [python/1. sampling.ipynb](python/1.%20sampling.ipynb). Be aware: This is not a scientific sample, it will just take every 10th data point.

## Explore
### Plot a map of the Zurich Airport
XY
### Plot a timetable for short range and long range Swiss airplanes
XY
### Export one flight and create an interactive 3D-Visualisation with QGIS
XY