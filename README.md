# Climate Projections

A python package which provides classes and methods with which to analyse climate projections in the netCDF format.

## Features



## Getting Started

For the latest release (as well as past versions), [please see the Releases page](https://gitlab.arup.com/climate-change-ade/climate-projections/-/releases). Alternatively, you can grab the latest release from the "master" branch of this code.

It is recommended that you install this package within its own anaconda environment, instructions are included below.

### Anaconda

Create a conda environment - in Annaconda Prompt:

```
conda create -n climate_projections python=2.7
```

Switch to the environment :
```
conda activate climate_projections
```

Install the package as per the instructions from the [Releases page](https://gitlab.arup.com/climate-change-ade/climate-projections/-/releases).

### Spyder 

If you are using spyder, you need to install spyder from conda. Version 3 seems to work best:

```
conda install spyder=3
```

Then you need to launch spyder from conda once you are in the right environment.

## Development

For development, first install the dependencies from the Anaconda package by downloading the latest [release](https://gitlab.arup.com/climate-change-ade/climate-projections/-/releases), extracting the zip file, navigating into the folder and running 

```
conda install --only-deps -c ./condaChannel climate_projections
```

Once this is done, you can install the latest version of the package from the gitlab using: 

```
pip install -e "git+https://gitlab.arup.com/climate-change-ade/climate-projections.git#egg=climateChangeProjections"
```



## Examples/Notebook installation
There are several examples in the ```example``` folder, which give a basic demonstration of the package use. These examples consist of scripts and jupyter notebooks.

Some of the examples use the ATR_utilities package which can be installed with the following command
```
python -m pip install git+https://gitlab.arup.com/BuildingPhysics/python/atr_utilities.git
```

To use the package in a notebook, install the ipython kernel into your environment
```
conda install ipykernel
python -m ipykernel install --user --name climateChangeProjections --display-name "Python (climateChangeProjections)"
```



## Contributing


## Authors




## License


## Acknowledgments

