# arcgis Notebooks Collection
## What this repo will be
A collection of sample iPython notebooks using the arcgis (ArcGIS API for Python) package for working with and visualizing different kinds of geographical data.

## Setup
In Anaconda Prompt:
```sh
# to set up Python environment using conda
conda env create -f environment.yaml 
```
```sh
# to activate environment after creation
conda activate arcgis
```

To enable environment in jupyter notebooks:
```sh
python -m ipykernel install --user --name=arcgis
```

To enable arcgis notebook extension:
```sh
jupyter nbextension enable arcgis --py --sys-prefix
```