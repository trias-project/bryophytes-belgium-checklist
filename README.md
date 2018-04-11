# Checklist of the Bryophytes of Belgium

## Rationale

This repository contains the functionality to standardize the _Checklist of the Bryophytes of Belgium_ published in [Soutiaux et al. 2007](https://www.jstor.org/stable/20794638?seq=1#page_scan_tab_contents) to a [Darwin Core checklist](https://www.gbif.org/dataset-classes) that can be harvested by [GBIF](http://www.gbif.org). It was developed for the [TrIAS project](http://trias-project.be).

## Workflow

[source data](https://github.com/trias-project/bryophytes-belgium-checklist/tree/master/data/raw) → Darwin Core [mapping script](http://trias-project.github.io/bryophytes-belgium-checklist/dwc_mapping.html) → generated [Darwin Core files](https://github.com/trias-project/bryophytes-belgium-checklist/blob/master/data/processed)

## Published dataset

* Dataset on the IPT (planned)
* Dataset on GBIF (planned)

## Repo structure

```
├── README.md         : Description of this repository
├── LICENSE           : Repository license
├── .gitignore        : Files and directories to be ignored by git
│
├── data
│   ├── raw           : Source data, input for mapping script
│   └── processed     : Darwin Core output of mapping script GENERATED
│
├── docs              : Repository website GENERATED
│
└── src
    ├── dwc_mapping.Rmd : Darwin Core mapping script, core functionality of this repository
    └── src.Rproj       : RStudio project file
```

## Installation

1. Clone this repository to your computer
2. Open the RStudio project file
3. Open the `dwc_mapping.Rmd` [R Markdown file](https://rmarkdown.rstudio.com/) in RStudio
4. Install any required packages
5. Click `Run > Run All` to generate the processed data
6. Alternatively, click `Build > Build website` to generate the processed data and build the website in `/docs`

## Contributors

[List of contributors](https://github.com/trias-project/bryophytes-belgium-checklist/contributors)

## License

[MIT License](https://github.com/trias-project/bryophytes-belgium-checklist/blob/master/LICENSE)
