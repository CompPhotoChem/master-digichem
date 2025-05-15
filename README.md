# Lecture on Digital Chemistry

M. Sc. Chemistry and M. Sc. Data Science

## Setup `digichem` conda environment on your own machine

The lecture uses jupyter-notebooks and works with the conda environment, called `digichem`.
To set up such an environment at your own machine, you first need a conda distribution.

We recommend, to [install miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install) or [install anaconda](https://www.anaconda.com/docs/getting-started/anaconda/install)

Next...

```
conda create -n digichem python=3.10
```
Download the requirements.txt, navigate to the folder of that file, activate your conda environment and install all the required packages from the requirements.txt file:

```
cd #your_path
conda activate digichem
pip install numpy pandas rdkit seaborn scikit-learn jupyter
```
