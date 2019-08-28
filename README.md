# AIM-UWYO
Repository for the AI Materials group in UWYO


## Installing Jupyter

Let's setup miniconda environment from https://conda.io/miniconda.html

```
bash Miniconda3-latest-Linux-x86_64.sh (for linux)
bash Miniconda3-latest-MacOSX-x86_64.sh (for Mac)
Download 32/64 bit python 3.6 miniconda exe and install (for windows)

Open Anaconda Prompt.

Now, let's make a conda environment just for AIMS-UWYO::
conda create --name my_aims python=3.7
conda activate my_aims
```

Now we can install Jupyter Notebook in our environment.

```
 conda install jupyter notebook
 conda install -c conda-forge jupyter_contrib_nbextensions
```

## Get git, play with example

Let's install git clone from https://git-scm.com/download/win (for windows) to clone repositories.
Once installed, restart Anaconda Prompt. Navigate to a known folder
```
We can use git to clone this repo on genetic algorithm particle swarm optimization.

git clone https://github.com/christianrfg/ga_pso.git
cd ga_pso  # change the directory to the repo
jupyter notebook  # run jupyter
```

## Install requirements

To install the required packages to run the notebook, GOOGLE it.
E.g. if the package name is numpy, google `conda install numpy`.

```
For this ga_pso repo example :
conda install numpy seaborn tabulate
```

