# `Cloudy-Maraston`

<div align="center">
    <img src="cloudy-maraston_transparent.png" alt="A yellow and orange cloud with the text 'Cloudy-maraston" width="400"/>
</div>

A repository showing how to recreate the plots from the paper Newman et al. 2024, "`Cloudy-Maraston`: Integrating nebular line and continuum emission with the M13 stellar population synthesis models"

## Prerequisites

This project used the code `synthesizer` which will be required to run the notebooks. To install `synthesizer`, first clone the latest version of `synthesizer`

    git clone https://github.com/flaresimulations/synthesizer.git

To install, enter the `synthesizer` directory and install with pip.

    cd synthesizer
    pip install .

The documentation for `synthesizer` can be found at https://flaresimulations.github.io/synthesizer/ 

Additionally these packages will need to be installed to run the notebooks:

    pip install numpy matplotlib unyt cmasher astropy seaborn 

## Grids and data

You will need to install the following grids from [here](https://sophie-newman.github.io/Cloudy-maraston.html) and place them in the `grids` directory:

* maraston13_kroupa-max_age:7.0_Cloudy-c23.01-sps.hdf5
* maraston13_kroupa-max_age:7.0.hdf5
* maraston13_salpeter-max_age:7.0.hdf5
* maraston13_kroupa-max_age:7.0_Cloudy-c23.01-sps-fixed-hydrogen_density.hdf5

and for the data comparison in Notebook 2 you will need the following SDSS and JADES files, downloaded into the `data` directory:

* galSpecInfo-dr8.fits
* galSpecLine-dr8.fits
* jades_dr3_medium_gratings_public_gn_v1.1.fits
* jades_dr3_medium_gratings_public_gs_v1.1.fits
  
These can be downloaded from the [SDSS DR8 website](https://www.sdss3.org/dr8/spectro/spectro_access.php) and the [JADES website](https://jades-survey.github.io/scientists/data.html). 

