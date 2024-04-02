# xdmod-notebooks R example
This directory contains an example R Markdown file demonstrating how to use the XDMoD Data Analytics Framework via the [`xdmod-data` package](https://pypi.org/project/xdmod-data/).

For examples using Python in Jupyter instead, see the main [README](../).

## Download
The latest version of this `xdmod-notebooks` repository can be downloaded from the [releases page](https://github.com/ubccr/xdmod-notebooks/releases) — under "Assets," click one of the "Source code" links.

## Setup
Follow the instructions below to set up your system to run the R Markdown file in RStudio Desktop using an Anaconda environment.

Install R and RStudio Desktop from [here](https://posit.co/download/rstudio-desktop/).

Install the following R libraries in RStudio Desktop (`Tools` > `Install Packages...`):
* `plotly`
* `rmarkdown`
* `reticulate`
* `tidyverse`

Install Anaconda following [these instructions](https://docs.anaconda.com/free/anaconda/install/index.html).

Next an Anaconda environment for `xdmod-notebooks` should be created either through the command line or the Anaconda Navigator GUI as instructed below.

* Command line
    ```
    conda activate
    conda create -y -n xdmod-notebooks python
    ```
* Anaconda Navigator
    1. Open Anaconda Navigator following [these instructions](https://docs.anaconda.com/free/anaconda/install/verify-install/).
    1. Click the `Environments` tab.
    1. Click `Create`.
        1. For the name, type `xdmod-notebooks`.
        1. Make sure only the box for Python is checked.
        1. Click `Create`.

### Obtain and store an API token
Follow [these instructions](https://github.com/ubccr/xdmod-data#api-token-access) to obtain an API token.

Create an environment file at `~/xdmod-data.env` with the following contents, replacing `<TOKEN>` with your token.
```
XDMOD_API_TOKEN=<TOKEN>
```

## Usage
* In RStudio Desktop, open and run the R Markdown file (`XDMoD-Data-First-Example-with-R-and-Reticulate.Rmd`) from your downloaded copy of this repository. If you are not familiar with running R Markdown files, the "Help" tab may provide useful information.

## Feedback / Feature Requests, Support, Contributing, License, and Reference
See the main [README](../).
