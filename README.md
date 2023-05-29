Data Product Template
==============================

This template has been created to support the design and implementation of data and metadata pipelines supporting our [Data Mesh Pattern](https://github.com/opendatahub-io-contrib/data-mesh-pattern)

Project Organization
------------

    ├── LICENSE
    ├── Pipfile                                 <- Pipfile stating package configuration as used by Pipenv.
    ├── Pipfile.lock                            <- Pipfile.lock stating a pinned down software stack with as used by Pipenv.
    ├── README.md                               <- The top-level README for developers using this project.
    ├── data                                    <- Original, immutable data files, to be used typically for examples
    ├── docs                                    <- Data product reference documentation
    ├── extract                                 <- Data extraction tasks, if required
    ├── load                                    <- Data loading tasks, if required
    ├── references                              <- Data dictionaries, manuals, and all other explanatory materials.
    ├── reports                                 <- Generated analysis as HTML, PDF, LaTeX, etc.
    └── transform                               <- DBT project used for data transformation

--------
