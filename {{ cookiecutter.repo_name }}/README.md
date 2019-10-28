# {{cookiecutter.project_name}}

{{cookiecutter.description}}

## Project Organization

    ├── LICENSE
    ├── README.md                               <- The top-level README for developers using this project.
    ├── data                                    <- datasets, etc.
    │
    ├── docs                                    <- A default Sphinx project with markdown; see sphinx-doc.org for details
    │
    ├── models                                  <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks                               <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                                              the creator's initials, and a short `-` delimited description, e.g.
    │                                              `1.0-jqp-initial-data-exploration`.
    │
    ├── requirements.txt                        <- The requirements file for reproducing the analysis environment, e.g.
    │                                              generated with `pip freeze > requirements.txt`
    │
    ├── {{cookiecutter.project_name}}           <- Source code for use in this project.
    │   │
    │   ├── data                                <- Scripts to download or generate data
    │   │
    │   ├── utils                               <- Scripts utilities used during data generation or training
    │   │
    │   ├── train                               <- Scripts to train models
    │   │
    │   ├── validate                            <- Scripts to validate models
    │   │
    │   └── visualize                           <- Scripts to create exploratory and results oriented visualizations
