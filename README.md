# MPilot-Geospatial-Tutorial

This demo uses Geopandas and MPilot to build a simple EEMS model.

## Prerequisites

1. Have a Python programming environment capable of conda and Jupyter Notebooks. I use [Anaconda Navigator](https://www.anaconda.com/products/individual-d) which contains JupyterLab. Install the following Python libraries to the conda environment.
    - Install [Pandas](https://pandas.pydata.org/): `conda install pandas` 
    - Install [Geopandas](https://geopandas.org/): `conda install geopandas` 
    - Install [MPilot](https://github.com/consbio/mpilot): `pip install mpilot`
2. Download the sample data and EEMS Manual through the `EEMS 2.02` link on the [EEMS website](https://consbio.org/products/tools/environmental-evaluation-modeling-system-eems/downloads).
3. Create a new Jupyter notebook called `Simple_EEMS_Model.ipynb`. Put the sample geodatabases from the downloaded `EEMS2.02_ArcGIS` in a project folder. Project folder structure should be:
    - `MyProject`
        - `1_RAW_Input.gdb`
        - `2_EEMS_Input.gdb`
        - `3_EEMS_Output.gdb`
        - `Simple_EEMS_Model.ipynb`