# NIST FRVT Analysis

This repository contains the data and code for analysing NIST's FRVT reports.

## Setup

Create conda environment

```shell
conda env create --file environment.yml
```

Clone the NIST FRVT repository containing the algorithm report cards. Note that the report cards are not in the `main` branch of the repository.
```shell
git clone --depth 1 --single-branch --branch nist-pages https://github.com/usnistgov/frvt.git frvt_pages
```

## Analysis notebooks

[Reading the NIST Report on 1:1 Face Recognition](https://martinsbruveris.com/?p=617)
- Cleaning up data extracted from the pdf file: `2020-10-31-frvt-11-cleanup-gender-race.ipynb`
- Analysis and graphs: `2020-10-31-frvt-11-gender-race.ipynb`

Exploring Bias using NIST's FRVT
- Parsing the downloaded report cards: `2020-11-01-parse-reportcards.ipynb`
- Analysis of cross-region FMR heatmaps: `2020-11-01-cross-region-analysis.ipynb`

## Author

Martins Bruveris (martins.bruveris@gmail.com)