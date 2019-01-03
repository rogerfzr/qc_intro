# Quantum Computing Intro

## Setup

View `py-primer.ipynb` for an introduction to python, numpy, and matplotlib.
Installation instructions are below, and also in `py-primer.ipynb`.

These instructions work best on Ubuntu machines (and it's highly encouaged to use Ubuntu for the class). However, only very slight modifications are necessary for Mac and Windows.

Once Anaconda and the necessary packages are installed, and you can get jupyter up and running, all the coding should be agnostic to the Operating System.

1. Download the most recent Anaconda distribution (with python 3.x) from: `https://www.anaconda.com/download/`. Alternatively, on Ubuntu command line execute: `wget https://repo.continuum.io/archive/Anaconda3-2018.12-Linux-x86_64.sh`

2. Install Anaconda distribution. On Ubuntu, run `sh Anaconda3-2018.12-Linux-x86_64.sh`

3. In the directory of your choice, clone this git repo: `git clone https://github.com/fleeb24/qc_intro`

4. In the cloned git repo, create a virtual conda environment with python 3.6 and all the required packages: `conda env create -f env_setup.yml`

5. Activate your conda environment with the command `source activate qc` (or `activate qc` for Windows).

6. Start a local jupyter server with the command: `jupyter notebook`. This should open the jupyter dashboard in your web browser. Alternatively, a link will be printed out in the terminal, which you can paste into your web browser to open the dashboard manually.

7. From the jupyter dashboard open `py-primer.ipynb` and start executing cells (using Shift+Enter).
