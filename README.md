# Compsci project 2

### Information

The written report is called ```report.pdf```. All figures can be found in ```./figures```. There is a jupyter notebook for every classification method located in ```./src/Notebooks```. 

The structure of this project is as follows:

```
compsci-project-2/
│
├── src 
│    │
│    ├── 00_visualization.ipynb - contains the calcium trace visualizations with respect to the stimulus classs
│    ├── 01_svm.ipynb - classification with svm
│    ├── 02_boosting.ipynb - classification with boosting
│    └── 03_ann.ipnb - classification with ann
└── figures
```

### Data and task description

In this repository, we present notebooks to visualize two photon calcium imaging data and perform classification task to identify the underlying stimulus category based on the neural representations obtained from this data.

### Getting started

First, I would recommend to get conda which is a package manager that makes it easy to install and manage various packages and organize them in environments. You can get it here
https://docs.conda.io/en/latest/miniconda.html

To create a conda environment that includes the necessary packages, open a terminal and run
```
conda env create -f environment.yml
```

To activate the environment, run
```
conda activate compsci-project
```

To start the jupyter notebook, run
```
jupyter notebook
```
