# Drivers of Equatorial Ocean Surface Winds – Reproduction Scripts

This repository contains the scripts required to reproduce the figures from:

**Winkler et al.**
*Uncovering the Drivers of the Equatorial Ocean Surface Winds.*
(doi: [10.1002/qj.4998](https://doi.org/10.1002/qj.4998))

## Repository contents

The scripts in this repository generate all figures presented in the paper.
They rely on processed secondary datasets derived from multiple primary sources.

## Environment setup

A conda-compatible environment file (`environment.yaml`) is provided to create a Python environment containing all required dependencies.

The environment can be created using:

```bash
conda env create -f environment.yaml
conda activate WIN25_uncovering_paper
```

Alternatively, the same environment can be created using **micromamba**:

```bash
micromamba create -f environment.yaml
micromamba activate WIN25_uncovering_paper
```

## Data availability

The processed secondary datasets used to reproduce the figures can be requested by contacting:

**[marius.winkler@mpimet.mpg.de](mailto:marius.winkler@mpimet.mpg.de)**

For access to the original primary datasets, please refer to the **Data Availability Statement** in the corresponding publication.

## Reproducibility

All figure scripts are provided as Jupyter Notebooks (`.ipynb`).
Running the scripts with the required datasets and the provided Python environment will reproduce the figures presented in the paper.