Welcome to Safety Path Generator Project
==============================

An ML model with user interface, to provide probability of certain crime occuring at any given time and date in future.     
The user interacts with the spatial map of the area(eg: Raleigh) to analyse the heatmap color coded with the probability of risk.    
This enables the user to avoids certains areas at certain points of the day, where their likelihood of becoming victims of a particular type of crime are higher. 

Demo
==============================

web interface: 


https://user-images.githubusercontent.com/18595435/116824759-d80b7280-ab59-11eb-9950-d8f5590fd146.mov

HeatMap sample : 
==============================

![image](https://user-images.githubusercontent.com/18595435/116824863-6849b780-ab5a-11eb-985a-3548af917c0e.png)


Install :
==============================
    pip install Flask
    

Usage :
==============================
    flask run

Contact :
==============================
    👤 Swathi Dinakaran 
    @ https://www.linkedin.com/in/swathi-dinakaran/
    
🤝 Contributors:
==============================
 Thanks to all the people who contribute.
 
 Jeffrey Wang(ideation,data),        Pratham Chhabria(ideation),         Jeremy Spooner(data)

Contributions, issues and feature requests are welcome.
Feel free to check issues page if you want to contribute.


AIatNCStateSpring2021SafetyPathGeneratorProject
==============================

This Spring 2021 AI at NC State project repository cotnains all of the machine learning prototyping code for the Safety Path Generator project. Acquiring tabular de-identified crime data from local college cities in North and South Carolina, cities in North and South Carolina, it seeks to harness the power of applied AI models to provide a heat map at any given time and place where incidences of crime per type are occuring and alert users of those areas, thereby providing with a path to take to avoid certains areas at certain points of the day where their likelihood of becoming victims of a particular type of crime are higher.

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
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------
