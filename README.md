# Nbval Demo for CW16

30 minutes hands-on with nbval, a py.test extension for documentiation validation
in Jupyter notebooks

## Get started

We will use miniconda to manage a new python environment (which will
not interact with your current python set up).

1. Get miniconda - follow the
   [miniconda quick install guide](http://conda.pydata.org/docs/install/quick.html)
2. Clone this repository `git clone git@github.com:owlas/nbval-demo.git`
3. and its submodules `git submodule init && git submodule update`
4. set up conda environment `conda env create -f environment.yml`
5. activate the new environment `source activate nbval-demo`

## Test your setup

Run the following: `py.test --nbval -v demo.ipynb`
