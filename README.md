create the Well_python environment:

`conda create -n Well_python -c conda-forge python=3.6 numpy scipy pandas matplotlib netcdf4 dask xarray cartopy ipython jupyter notebook jupyterlab`

If using the anaconda navigator, I recommend editing the list of channels to include the `conda-forge` channel, to do so, first select `channels` in the right window, then `add`, enter `conda-forge` and hit enter.

Then go to the `environment` tab on the left, then choose `create` at the bottom. Make sure to choose a `Python 3.6` environment, and find and install all the package above in this new environment.

The packages listed below can be installed either from the command line (e.g. `conda install -n Well_python -c conda-forge *package_name*`) or using the anaconda navigator.

+ additional packages to read and write excel files (from pandas):
    + `xlrd`
    + `openpyxl`
    + `excelwriter`

+ additional packages for xarray:

make sure you have the `netcdf4` package installed, as well as `dask`. `nc-time-axis` is also needed for some time-axis formatting.