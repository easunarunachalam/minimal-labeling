Setup a conda environment with `napari`, `xarray`, and `jupyterlab`.

```
conda create -n minimal_labeling
conda activate minimal_labeling
conda install pip
python -m pip install "napari[all]"
python -m pip install xarray jupyterlab
```
