# First EDA project

This repository contains the results of my first Exploratory Data Analysis (EDA) project, while attending the neuefische Data Science Bootcamp.

## Data
For this task we were given a data set containing records of house sales in King County, near Seattle. It included house prices, date it was sold, size of lot/living space, average lot/living space nearby, latitude and longitude, etc.

## Task
As described in [assignment.md](assignment.md):
1. Create a new repo using this [template](hhttps://github.com/neuefische/ds-eda-project-template).

2. Through EDA/statistical analysis above please come up with **AT LEAST 3 insights** regarding the overall data. One should be geographical.

3. In addition also come up with **AT LEAST 3 recommendations** for your stakeholder.

## Virtual Environment

Modified [requirements.txt](requirements.txt) file from ds-visualization repository. Essentially removed SQL packages. 

To install the environment, ran the following commands:

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Results

A detailed description of my analysis is found in [EDA.ipynb](EDA.ipynb), and the slides for my presentation to the stakeholder is found in [EDA_project_neuefische.pdf](EDA_project_neuefische.pdf).
