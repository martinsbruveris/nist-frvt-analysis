# NIST FRVT Analysis

This repository contains the data and code for analysing NIST's FRVT reports.

## Setup

Create conda environment

```shell
conda env create --file environment.yml
```

Clone the NIST FRVT repository with report cards. Note that it is not the `main`m branch of the repository.
```shell
git clone --depth 1 --single-branch --branch nist-pages https://github.com/usnistgov/frvt.git frvt_pages
```

## Author

Martins Bruveris (martins.bruveris@gmail.com)