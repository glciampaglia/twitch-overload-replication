# Code and data for [Nematzadeh et al. (2019)](http://dx.doi.org/10.1098/rsos.191412)

This repository contains a Jupyter notebook that replicates the main results of
the following paper:

    Nematzadeh, Azadeh, Giovanni Luca Ciampaglia, Yong-Yeol Ahn, and Alessandro
    Flammini. Information Overload in Group Communication: From Conversation to
    Cacophony in the Twitch Chat (2019) _R. Soc. open sci._ 6: 191412.

The following BibTeX code can be imported into a citation manager for reference:

```bibtex
    @Article{Nematzadeh2019,
        Title         = {Information Overload in Group Communication: From
                         Conversation to Cacophony in the Twitch Chat},
        Author        = {Nematzadeh, Azadeh and Ciampaglia, Giovanni Luca and
                         Ahn, Yong-Yeol and Flammini, Alessandro},
        Year          = {2019},
        Month         = oct,
        Journal       = {R. Soc. open sci.},
        Number        = {6},
        Pages         = {191412},
        Doi           = {10.1098/rsos.191412}
    }
```

## 1. Installation

The notebook was written in Python 3. A number of dependencies are to be
installed before running it. A list of package requirements is provided. The
simplest method is to run a package manager such as pip or conda. It is
recommended that all dependencies are installed in a separate Python
environment.

The best way to do so is to use the Miniconda, which is a small bootstrap
version of the largest Anaconda Python distribution. Miniconda is available for
most major operative systems (Windows, Linux, MacOS) 

1. Download Miniconda from here: https://conda.io/miniconda.html
2. Follow the installation instruction for your platform:
   https://conda.io/docs/user-guide/install/index.html
3. Clone or download this repository
```
git clone git@github.com:glciampaglia/twitch-overload.git
```
4. Open a terminal and run:
```
    cd twitch-overload
    conda env create --file environment.yml
    conda activate twitch-overload
```

This should install all needed packages and activate the environment.

## 2. Download the data

To run the code in the notebook you must download the data from
[Zenodo](https://doi.org/10.5281/zenodo.1182793). The files need to be
placed in the folder `data` within this repository. Please note that only
aggregated count data are provided. These will allow to replicate the main
findings of the article. For more information please refer to data sharing
section of the article.

## 3. Execution

To open the notebook, follow the instructions above for installing the Python
environment and for obtaining the dataset files. From the location
where you downloaded this repository launch Jupyter Notebook with:

```
    conda activate twitch-overload
    jupyter notebook
```

This will open the notebook interface in your browser. It will show the
contents of this repository. Click on the entry called _Plots.ipynb_.
