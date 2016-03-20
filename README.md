# Nbval Demo for CW16

30 minutes hands-on with nbval, a py.test extension for documentiation validation
in Jupyter notebooks

## Get started

1. **Clone this repo**
    - `git clone git@github.com:owlas/nbval-demo.git`
2. **Get miniconda**
   - If you already have (mini)conda, then you can skip this step
   - Follow the [miniconda quick install guide](http://conda.pydata.org/docs/install/quick.html)
3. **Set up conda environment**
    - `conda env create -f environment.yml`
4. **Activate the new environment**
    - `source activate nbval-demo`

## Test your setup

Run the following: `py.test --nbval -v demo.ipynb`
