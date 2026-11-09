# openEO gallery

Example Jupyter notebooks that build [openEO](https://openeo.org) process graphs and show the result as dynamic tile layers in a [JupyterGIS](https://github.com/geojupyter/jupytergis) map.

The notebooks use the openEO backend at `https://openeo.mpc.ds.io/`.

> **Note:** You need a Microsoft Planetary Computer account to access the backend at `https://openeo.mpc.ds.io/`. If you don't have one, [create a Microsoft account](https://signup.live.com/).

## Notebooks

| Notebook | Description |
|----------|-------------|
| [openeo.ipynb](notebooks/openeo.ipynb) | Sentinel-2 true color image over New York City (April to December 2022), with a `color_formula` (gamma, sigmoidal contrast, saturation). A minimal example of `add_openeo_tile_layer`. |
| [ndci_venice_lagoon.ipynb](notebooks/ndci_venice_lagoon.ipynb) | Cyanobacteria chlorophyll-a (NDCI) over the Venice lagoon, June 2026. Water detection, Floating Algae Index (FAI), NDCI, chlorophyll-a concentration and a color map. Uses `firstpixel` to make a first-valid-pixel mosaic. |
| [snow_classifier_sentinel2.ipynb](notebooks/snow_classifier_sentinel2.ipynb) | Snow classification around Bovec, Slovenia (26–30 October 2019) with NDSI and NDVI. Snow is shown in light beige over a brightened true color composite. Adapted from the openEO-UDP snow classifier notebook (CC-BY-SA-4.0). |
| [ndsi_sentinel2.ipynb](notebooks/ndsi_sentinel2.ipynb) | Normalized Difference Snow Index (NDSI) over Haka Conservation Park, New Zealand (19–21 September 2019). Snow (NDSI > 0.42) is shown in blue over a brightened true color composite. Adapted from the openEO-UDP NDSI notebook (CC-BY-SA-4.0). |
| [lava_flow_sentinel2.ipynb](notebooks/lava_flow_sentinel2.ipynb) | Lava flows of the Cumbre Vieja eruption, La Palma, Spain (10 October 2021). Lava intensity from SWIR Band 12 is shown as a heatmap (red for cool crust to yellow for active molten lava) over a blend of true color and a SWIR composite, with water tinted blue. Adapted from the openEO-UDP lava visualization notebook (CC-BY-SA-4.0). |

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/geojupyter/openeo-gallery/main)
[![notebook.link](https://img.shields.io/badge/notebook-link-e2d610?logo=jupyter&logoColor=white)](https://notebook.link/github/geojupyter/openeo-gallery/tree/main/lab/).
