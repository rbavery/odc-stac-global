This is a prettynoodly wip notebook where I'm figuring out what's the most performant and easy to use way to query fetch stack and store time series of geospatial rasters from STAC collections (in Python).

## Setup

Install Pixi. It's like uv but uses conda so installing gdal is easy. It won't bite, or affect your other python installations.

`curl -fsSL https://pixi.sh/install.sh | bash`

then in this repo install the local project environment from the pixi.toml

`pixi install`

`pixi run jupyter lab`

Start in odc-stac-on-dask.ipynb, skip over cells that fail since you don't need them and don't need to run the coast_aois.ipynb notebook.
