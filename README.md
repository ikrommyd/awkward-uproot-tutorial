# Awkward Array and Uproot tutorial

## Recommended: run the notebooks on your computer with `pixi`

First, clone this repository.

```shell
git clone https://github.com/ikrommyd/awkward-uproot-tutorial.git
cd awkward-uproot-tutorial
```

Then, install the `pixi` tool if you haven't already. You can do this with `pip`:
```

Make sure you've [installed pixi](https://pixi.sh/latest/installation/) on your computer.

Then you can install the environment and start a local JupyterLab session with:

```shell
pixi run start
```
## Alternative: run the notebooks on your computer with `uv` or a standard Python `venv`

Make sure you've [installed uv](https://docs.astral.sh/uv/getting-started/installation/) on your computer.

Then you can install the environment and start a local JupyterLab session with uv:

```shell
uv venv --python=3.13
source .venv/bin/activate
uv pip install -r requirements.txt
jupyter lab
```

or with a standard Python `venv`:

```shell
python3.13 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Alternative: run the notebooks on your computer with `conda`/`mamba`

Make sure you've [installed Miniforge](https://conda-forge.org/download/) on your computer.

Then you can install the environment and start a local JupyterLab session with:

```shell
conda env create -f environment.yml
conda activate awkward-uproot-tutorial
jupyter lab
```

## Alternative: run the notebooks on MyBinder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ikrommyd/awkward-uproot-tutorial/HEAD)

Click on the Binder badge above or go to the url below to launch a JupyterLab session in your browser with the notebooks and all dependencies pre-installed using MyBinder:
```
https://mybinder.org/v2/gh/ikrommyd/awkward-uproot-tutorial/HEAD
```
