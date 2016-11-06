# Plot data from EarthServer using Magics

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/kynan/magics-binder)

Example notebook retrieving data from [EarthServer](http://earthserver.ecmwf.int)
and plot it using [Magics](https://software.ecmwf.int/wiki/display/MAGP).

Launch in [Binder](https://mybinder.org) by clicking the button above or run a
local [Jupyter notebook](http://jupyter.org) server. Assuming you are using
[Anaconda](https://www.continuum.io/anaconda-overview) or
[Miniconda](http://conda.pydata.org/miniconda.html), the steps are as follows:

    git clone https://github.com/kynan/magics-binder
    cd magics-binder
    conda env create -n magics -f environment.yml
    source activate magics
    jupyter notebook
