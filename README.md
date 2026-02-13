# S-index Parameters Analysis

**Jupyter notebook with code to analyze the parameters and behavior of the proposed S-index**

[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![DOI][zenodo-badge]][zenodo-doi]

[stars-shield]: https://img.shields.io/github/stars/data-S-index/s-index-parameters-analysis.svg?style=flat-square
[stars-url]: https://github.com/data-S-index/s-index-parameters-analysis/stargazers
[issues-shield]: https://img.shields.io/github/issues/data-S-index/s-index-parameters-analysis.svg?style=flat-square
[issues-url]: https://github.com/data-S-index/s-index-parameters-analysis/issues
[license-shield]: https://img.shields.io/github/license/data-S-index/s-index-parameters-analysis.svg?style=flat-square
[license-url]: https://github.com/data-S-index/s-index-parameters-analysis/blob/master/LICENSE
[zenodo-badge]: https://zenodo.org/badge/DOI/10.5281/zenodo.18627001.svg
[zenodo-doi]: https://doi.org/10.5281/zenodo.18627001

## ℹ️ About
This repository contains the Jupyter notebook we developed to analyze the parameters and behavior of our proposed S-index. The outputs were included in our NIH S-index Challenge Phase 2 proposal. We refer to the [S-index Hub](https://github.com/data-S-index/hub) for more information about our S-index and the Challenge.

## 🚀 Using the Jupyter notebook

### Prerequisites 
We recommend using Anaconda to create and manage your development environment and using JupyterLab to run the notebook. All the subsequent instructions are provided assuming you are using [Anaconda (Python 3 version)](https://www.anaconda.com/products/individual) and JupyterLab.

### Clone repo
Clone the repo or download as a zip and extract.

### cd into the code folder

Open Anaconda prompt (Windows) or the system Command line interface then naviguate to the code
```sh
cd .s-index-parameters-analysis

```

### Setup conda environment
```sh
conda env create -f environment.yml
```

### Setup kernell for Jupyter lab
```sh
conda activate s-index-parameters-analysis
conda install ipykernel
ipython kernel install --user --name=s-index-parameters-analysis
conda deactivate
```
### Launch Jupyter lab
Launch Jupyter lab and naviguate to open the main.ipynb file. Make sure to change the kernel to the one created above (e.g., see [here](https://doc.cocalc.com/howto/jupyter-kernel-selection.html#cocalc-s-jupyter-notebook)). 

## 📦 Inputs/outputs
There are no inputs for this code. Outputs of the code include plots displayed in the notebook but also saved as files. These saved plot files are included in the [output](output) folder. 

## 📋 Standards followed
We followed the [FAIR-BioRS guidelines](https://fair-biors.org/) (including CITATION.cff and codemeta.json, archiving code on Zenodo, etc.). We used the [JupyterLab code formatter](https://github.com/ryantam626/jupyterlab_code_formatter) along with the [Black](https://github.com/psf/black) and [isort](https://github.com/PyCQA/isort) formatters to facilitate compliance with PEP8.

## 📜 License
This work is licensed under
[MIT](https://opensource.org/licenses/mit). See [LICENSE](LICENSE) for more information.

## 🤝 Feedback and contribution
Use the [GitHub issues](https://github.com/data-S-index/s-index-parameters-analysis/issues) for submitting feedback or making suggestions. You can also work the repository and submit a pull request with suggestions.

## 📝 How to cite
If you use this code, please follow the citation instructions included in the [CITATION.cff](CITATION.cff) file.
