<a target="_blank" href="https://colab.research.google.com/github/duggalrohi/sklearn_tutorial">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



```python
from google.colab import drive
drive.mount('/content/drive/')
```

Clone repo

```python
%git clone https://github.com/duggalrohi/sklearn_tutorial.git
```

Go to `drive`, scroll to `notebooks` directory, right click on `01-Preliminaries.ipynb`, and open with colab.

In a new cell, 
```python
from google.colab import drive
drive.mount('/content/drive/')
```

Navigate to `notebooks` directory
```python
%cd '/content/drive/MyDrive/sklearn_tutorial/notebooks/
```

Run you notebook.





# Scikit-learn Tutorial

Original tutorial material from *Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

This repository contains notebooks and other files associated with the [Scikit-learn](http://scikit-learn.org) tutorial.
The notebooks have been updated by NeSI (http://github.com/nesi/sklearn_tutorial.git) to run with recent versions of Python and dependencies.

Recordings of the original workshop are available on Youtube:

- https://www.youtube.com/watch?v=L7R4HUQ-eQ0 (3 hours version)
- https://www.youtube.com/watch?v=HC0J_SPm9co (1.5 hours version)


## Installation Notes

To run the notebooks on your laptop, you will need to clone the repository:

```
git clone https://github.com/nesi/sklearn_tutorial.git
```

Note also that some of the code in these notebooks will not work outside the directory structure of this tutorial, so it is important to clone the full repository if possible.

Then, we recommend that you download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
Once Miniconda is installed, navigate to your local copy of the repository and use the following command to create a Conda environment with all required packages:

```
conda env create -f environment.lock.yml
```

Then activate your environment:

```
conda activate skl_tut
```

The tutorial material has been tested with the following package versions:

- Python version 3.10.5
- `numpy` version 1.22.4: https://www.numpy.org
- `scipy` version 1.8.1: https://www.scipy.org
- `matplotlib` version 3.5.2: https://matplotlib.org
- `scikit-learn` version 1.1.1: https://scikit-learn.org
- `jupyterlab` version 4.1.2: https://jupyterlab.readthedocs.io
- `ipywidgets` version 8.1.2: https://ipywidgets.readthedocs.io
- `pandas` version 1.4.2: https://pandas.pydata.org/


## Notebook Listing

Start `JupyterLab` using:

```
jupyter lab 
```

Then navigate the directory structure.
The notebooks are under the directory `notebooks`.
Click on `Index.ipynb` to get started.
