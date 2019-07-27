# deepberlin-teamb-sfod
Team B Repo for DeepBerlin Hackathon Challenge - Single Frame Object Detection

Loosely based on
[cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science/).

### Notebooks

```
├── notebooks <- Jupyter notebooks. Naming convention is a number (for ordering),
│                the creator's initials, and a short `-` delimited description, e.g.
│                `1.0-jqp-initial-data-exploration`.
```

### Data

All info on task and data sources can be found in documents in /references/.

Please use data folder structure as it follows:

```
data
├── external       <- Data from third party sources.
├── interim        <- Intermediate data that has been transformed.
├── processed      <- The final, canonical data sets for modeling.
└── raw            <- The original, immutable data dump.
    ├── airbus     <- Kaggle Airbus Challenge Dataset
    ├── pipistrel  <- Pipistrel Dataset
    └── ...        <- X Dataset
```
