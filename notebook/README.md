All processing is performed using open-source Python tools

Core dependencies
Python ≥ 3.9
xarray
numpy
geopandas
matplotlib
shapely
pyproj
mintpy

Environment setup
conda env create -f environment.yml
conda activate insar
Note: This project does not require raw SAR data or interferogram generation. No ISCE2, GAMMA, or raw Sentinel-1 processing is used.
