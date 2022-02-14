[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![DOI](https://zenodo.org/badge/404439394.svg)](https://zenodo.org/badge/latestdoi/404439394)

# Dataset: Biomechanical constitutive modeling of the gastrointestinal tissues
This is the dataset associated with our review manuscript on the biomechanical constitutive modeling of GI tissues [1]. It is structured according to the SPARC Data Structure [2] and curated using the SPARC data curation software SODA v4.7.0 [3,4]. We refer to the manuscript for details about the dataset content.

## Using the Jupyter notebook under the code folder

### Prerequisites 
We recommend using Anaconda to create and manage your development environment. All the subsequent instructions are provided assuming you are using [Anaconda (Python 3 version)](https://www.anaconda.com/products/individual).

### Clone repo
Clone the repo or download as a zip and extract.

### cd into the code folder

Open Anaconda prompt (Windows) or the system Command line interface then naviguate to the code
```sh
cd .GI-review-dataset/code

```

### Setup conda env
```sh
$ conda env create -f environment.yml
```

### Setup kernell for Jupyter lab
```sh
$ conda activate env-GI-review
$ conda ipython kernel install --user --name=<any_name_for_kernel>
$ conda deactivate
```
### Launch Jupyter lab
Launch Jupyter lab and naviguate to open the post-processing-code.ipynb file under the code folder. Make sure to change the kernel to the one created above (e.g., see https://doc.cocalc.com/howto/jupyter-kernel-selection.html#cocalc-s-jupyter-notebook)


## References
[1] Patel, B., Gizzi, A., Hashemi, J., Awakeem, Y., Gregersen, H., & Kassab, G. (2021). *Biomechanical constitutive modeling of the gastrointestinal tissues: where are we?*. preprints.org (https://doi.org/10.20944/preprints202109.0391.v1)

[2] Bandrowski, A., Grethe, J.S., Pilko, A., Gillespie, T.H., Pine, G., Patel, B., Surles-Zeiglera, M. and Martone, M.E., 2021. *SPARC data structure: Rationale and design of a fair standard for biomedical research data*. bioRxiv (https://doi.org/10.1101/2021.02.10.430563)

[3] https://github.com/bvhpatel/SODA

[4] Patel, B., Ngo, T., Soundarajan, S. *SODA (Software to Organize Data Automatically) for SPARC: v4.7.0*. Zenodo (https://doi.org/10.5281/zenodo.5392287). 


[contributors-shield]: https://img.shields.io/github/contributors/bvhpatel/GI-review-dataset.svg?style=flat-square
[contributors-url]: https://github.com/bvhpatel/GI-review-dataset/graphs/contributors
[stars-shield]: https://img.shields.io/github/stars/bvhpatel/GI-review-dataset.svg?style=flat-square
[stars-url]: https://github.com/bvhpatel/GI-review-dataset/stargazers
[issues-shield]: https://img.shields.io/github/issues/bvhpatel/GI-review-dataset.svg?style=flat-square
[issues-url]: https://github.com/bvhpatel/GI-review-dataset/issues
[license-shield]: https://img.shields.io/github/license/bvhpatel/GI-review-dataset.svg?style=flat-square
[license-url]: https://github.com/bvhpatel/GI-review-dataset/blob/master/LICENSE
