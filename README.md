This repository contains python notebooks:

1. Hadamard S matrix generation script
2. Quantitative Analysis vector checking tool to identify positive samples (HadamardPoolingAnalysisChecking.ipynb)
3. Analysis vector checking tool for fluorescent probes (widgetA.ipynb).
4. Analysis vector checking tool for type 1 and type 2 matrices (widgetB.ipynb)


An interactive version of the quantitative analysis vector checking tool can be accessed using the button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/byorke/Hadamard/HEAD?labpath=HadamardPoolingAnalysisChecking.ipynb)

This tool allows you to:
- Determine which size matrix can be used for a given number of samples.
- How many samples should be used.
- Which samples should be added to each pool.

You can also:
- Input an analysis vector and determine which (if any) samples are positive.

# Dependencies:

- numpy

- ipywidgets

- IPython

- jupyter (or jupyterlab) → to run .ipynb notebooks

Optional:

- matplotlib

## Using pip
pip install numpy ipywidgets jupyterlab

## Or with conda
conda install numpy ipywidgets jupyterlab -c conda-forge

## Publication

Multiplex Detection of Viruses using Hadamard Matrices. G. S. Beddard & B. Yorke

Preprint: https://www.medrxiv.org/content/10.1101/2024.10.21.24315883v2

Email: g.s.beddard@leeds.ac.uk, b.a.yorke@leeds.ac.uk
