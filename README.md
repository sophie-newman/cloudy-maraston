# cloudy-maraston
A repository showing how to recreate the plots from the paper Newman et al. 2024, "Cloudy-Maraston: Integrating nebular line and continuum emission with the M13 stellar population synthesis models"

This project used the code synthesizer which will be required to run the notebooks. To install synthesizer, first clone the latest version of `synthesizer`

    git clone https://github.com/flaresimulations/synthesizer.git

To install, enter the `synthesizer` directory and install with pip.

    cd synthesizer
    pip install .

The documentation for synthesizer can be found at https://flaresimulations.github.io/synthesizer/ 

You will need to install the following grids from [here](https://sophie-newman.github.io/cloudy-maraston.html):

* maraston13_kroupa-max_age:7.0_cloudy-c23.01-sps
* maraston13_kroupa-max_age:7.0
* maraston13_salpeter-max_age:7.0
* maraston13_kroupa-max_age:7.0_cloudy-c23.01-sps-fixed-hydrogen_density
  

Then add these to a grids directory within the cloudy-maraston repository

    mkdir grids
