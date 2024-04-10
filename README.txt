# AMP for Change Point Inference in High-Dimensional Linear Regression
Includes code used to produce experiments in "Inferring Change Points in High-Dimensional Linear Regression via Approximate Message Passing" by Gabriel Arpino, Xiaoqi Liu, and Ramji Venkataramanan.

All plots are generated using Python or Jupyter Notebook files.

# Required Packages
In order to run the files, the following Python libraries are required: _numpy_, _jax_, _scipy_, _matplotlib_, _functools_, _tqdm_. 

# Scripts
## Minimum Working Example.ipynb
Includes a minimum working example for running AMP and inferring the locations of two change points using various different signal priors, and a uniform prior on the change point locations.  

## estimation_experiments.ipynb
Contains the code for producing Figure 1 in the paper. The first cell can be run to save the file "coverage_data_v2.npz", which can then be plotted using the plot_estimation_results.ipynb file. 

## real_data_experiment.ipynb
Contains code for producing Figure 6 in the paper. 

## hpc_*.py
Contains code used to schedule cloud compute jobs for producing Figures 4 and 5 in the paper. 