# HealthReach Data Visualizations
Final Project, FAES BIOF 309 Introduction to Python, Fall 2018
Laura Bartlett (bartlettl@mail.nih.gov) and In Hye Cho (in-hye.cho@nih.gov)

HealthReach (http://healthreach.nlm.nih.gov) is a National Library of Medicine (NLM) resource that provides access to free low literacy, multilingual patient education materials to be used by healthcare providers. The purpose of this project is to efficiently explore HealthReach data and create easy-to-read visualizations using Python for data anyalsis also known as "pandas".

##Motivation
Healthcare providers often self-identify as being "not tech savvy" and are intimidated by technologies such as an application programming interface (API). This project exists to decrease the technology barrier healthcare providers face when discussing the use of an application programming interface (API) to search and retrieve HealthReach content. The use of easy-to-read and non-intimidating visuals will help end-users become more familiar with HealthReach data.

##Development Environment
Jupyter Notebook on Windows 10, Anaconda, PyCharm

##License
MIT © 



final-project-template
==============================

- Google Colab [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BIOF309/final-project-nlm/blob/master/NLM%20data_FINAL.ipynb)
- Jupyter Lab [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOF309/final-project-nlm/master?urlpath=lab/tree/NLM%20data_FINAL.ipynb)
- Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOF309/final-project-nlm/master?filepath=NLM%20data_FINAL.ipynb)

A template I recommend for final projects. Feel free to modify as needed!
Based on Cookiecutter Data Science:

repo: https://github.com/drivendata/cookiecutter-data-science

site: http://drivendata.github.io/cookiecutter-data-science/



Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
