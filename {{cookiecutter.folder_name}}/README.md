# {{cookiecutter.project_name}}

_project description_


### Directory structure
------------

```
{{cookiecutter.folder_name}}
├── data (added to .gitignore)
│   ├── processed           <- The final, canonical data sets for modeling.
│   └── raw                 <- The original, immutable data dump.
│
├── analysis                <- Jupyter notebooks, Excel, etc. 
|   ├── 1-dataprep.ipynb    <- Generates interim and processed data.
|   └── 2-eda.ipynb         <- Exploratory data analysis.             
│
└── reports                 <- Generated analysis as HTML, PDF, LaTeX, etc.

(optional folders)
├── README.md               <- The top-level README for developers using this project.
|
├── requirements.txt        <- The requirements file for reproducing the analysis environment, 
|                              e.g. generated with `pip freeze > requirements.txt`
|
├── references              <- Data dictionaries, manuals, and all other explanatory materials.
│
├── docs                    <- Documentation for any code that is part of your deliverables.
|                              Use a tool such as Sphinx or roxygen2 to generate 
|                              documentation from comments in your code so you don't have
|                              to maintain it manually.
├── env*                    <- Location for virtualenv's, database info, etc.
├── models*                 <- Trained and serialized models, model predictions, or model summaries
│
└── src                     <- Custom source code module for import into this project.
    ├── __init__.py         <- Makes src a Python module
    ├── data                <- Scripts to download or generate data
    │   └── make_dataset.py
    ├── features            <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    ├── models              <- Scripts to train models and then use trained models to make
    │   │                   predictions
    │   ├── train_model.py
    │   └── predict.py
    └── visualization       <- Scripts to create exploratory and results oriented figures
        └── visualize.py
        
Note: directories with asterisks* need to be listed in .gitignore to be excluded from source control.
```


------------
<p><small>Project based on the <a target="_blank" href="https://github.com/chris-chua/cookiecutter-datascience">Cookiecutter: DataScience project template</a>.</small></p>