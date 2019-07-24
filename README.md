# B1 filtering notebook

# Environment setup

Not included in instruction: cloning the repo and checking the branch.

* (Recommended) Create a conda virtual environment.
  * `conda create -n sos_matlab python=3.6`
  * `conda activate sos_matlab`
  * `conda install ipython=7.2.0`
* Setup the MATLAB Engine API for Python
  * `cd /Applications/MATLAB_R2018b.app/extern/engines/python/`
  * `python setup.py install`
* Install neessary Python packages
  * `pip install octave_kernel sos==0.17.7 sos-notebook==0.17.2 sos-python==0.9.12.1 sos-bash==0.12.3          sos-matlab==0.9.12.1 sos-ruby==0.9.15.0 sos-sas==0.9.12.3 sos-julia==0.9.12.1 sos-javascript==0.9.12.2                 sos-r==0.9.12.2 scipy plotly==3.10.0 dash dash_core_components dash_html_components                 dash_dangerously_set_inner_html dash-renderer flask imatlab;`
* Install the MATLAB and SOS Jupyter kernels
  * `python -mimatlab install`
  * `python -m sos_notebook.install`
* Start a Jupyter session
  * `jupyter notebook`
