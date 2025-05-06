# `Cloudy-Maraston`

<div align="center">
    <img src="cloudy-maraston_transparent.png" alt="A yellow and orange cloud with the text 'Cloudy-maraston" width="400"/>
</div>

A repository showing how to recreate the plots from the paper [Newman et al. 2025](https://ui.adsabs.harvard.edu/abs/2025arXiv250103133N/abstract), "`Cloudy-Maraston`: Integrating nebular continuum and line emission with the Maraston stellar population synthesis models".

## Prerequisites

This project used the code `synthesizer` which will be required to run the notebooks. To install `synthesizer`, first clone the latest version of `synthesizer`

    git clone git@github.com:synthesizer-project/synthesizer.git

and checkout the version used when writing this set of notebooks: 

    git checkout v0.6.0-beta

To install, enter the `synthesizer` directory and install with pip.

    cd synthesizer
    pip install .

The documentation for the latest version of `synthesizer` can be found at https://synthesizer-project.github.io/synthesizer/

Additionally these packages will need to be installed to run the notebooks:

    pip install numpy matplotlib unyt cmasher astropy seaborn pandas

## Grids and data

You will need to download the grids from [here](https://zenodo.org/records/13744975) and place them in the `grids` directory, and for the data comparison in Notebook 2 you will need the following SDSS and JADES files, downloaded into the `data` directory:

* galSpecInfo-dr8.fits
* galSpecLine-dr8.fits
* jades_dr3_medium_gratings_public_gn_v1.1.fits
* jades_dr3_medium_gratings_public_gs_v1.1.fits
  
These can be downloaded from the [SDSS DR8 website](https://www.sdss3.org/dr8/spectro/spectro_access.php) and the [JADES website](https://jades-survey.github.io/scientists/data.html). 

