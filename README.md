# Lecture on Digital Chemistry

M. Sc. Chemistry and M. Sc. Data Science

## Setup `digichem` conda environment on your own machine

The lecture uses jupyter-notebooks and works with the conda environment, called `digichem`.
To set up such an environment at your own machine, you first need a conda distribution.

We recommend, to [install miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install) or [install anaconda](https://www.anaconda.com/docs/getting-started/anaconda/install)

First, create a new conda environment and activate it. For example:

```
conda create -n digichem python=3.10
conda activate digichem
```

With the environment activated, install the necessary packages. If you're using a requirements.txt file, navigate to its directory and run:
```
pip install requirements.txt
```

Alternatively, you can install the packages directly:

```
pip install numpy pandas rdkit seaborn scikit-learn jupyterlab notebook py3Dmol
```

## (Optional) Enable MyST Extensions for Enhanced Notebook Styling

To enable enhanced markdown rendering in Jupyter Notebooks (e.g., for nicer formatting and structure), you can install the MyST extensions. These are optional and not required to run the code:

- https://mystmd.org/guide/quickstart-jupyter-lab-myst
- jupyterlab-myst (extension for nice visualization of excercises, notes, ...)


> [!TIP]
> To verify that the extension is registered with Jupyter, use:
> ```
> jupyter labextension list
> ```
> You should see the following text in the output:
> ```
> jupyterlab-myst v1.x.x enabled OK
> @jupyter-notebook/lab-extension v7.1.3 enabled OK
> ```
> If not install it and activate it. Note, lab-extension is compatible with notebook <= 7.1.3
> ```
> # Jupyter Notebook version 7.1.3
> pip install notebook==7.1.3
>
> # nbextensions for ipynb
> pip install jupyter_contrib_nbextensions
>
> # extension for markdown
> pip install jupyterlab-myst
> jupyter labextension install @jupyterlab/myst-extension
> ```
>
