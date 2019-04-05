create the Well_python environment: 

On linux:

```
conda env create -f environment_linux.yml

```

On Mac: 

```
conda env create -f environment_Mac.yml

```

On Windows you can try the Mac environment, and if not working default to: 

```
conda create -n Well_python -c conda-forge python=3.6 numpy scipy pandas matplotlib openpyxl xlsxwriter netcdf4 dask xarray cartopy jupyter notebook jupyterlab 
```



