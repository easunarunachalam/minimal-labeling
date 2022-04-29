# Setup

Setup a conda environment with `napari`, `xarray`, and `jupyterlab`.

```
conda create -n minimal_labeling
conda activate minimal_labeling
conda install pip
python -m pip install "napari[all]"
python -m pip install xarray jupyterlab netCDF4
```

# Labeling images

1. Change the path to the file containing the dataset you'd like to segment
2. Run the first four cells in the notebook `segmentation.ipynb`
3. Select the `labels` layer in napari and paint/fill as desired (instructions/keyboard shortcuts are in the [napari documentation](https://napari.org/index.html)
4. Confirm that labeling is saved by running the fifth cell in the notebook and verifying that the output is >> 0
5. Run the last cell to save the dataset with the new labels.
