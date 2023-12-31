
# EPFL ML_Course(CS-433) Project 2

## Introduction

Hello! Welcome to our team's repository of Project 2 of 2023 Machine learning course. 
In this project, we analyze the impressions of the view-out scenes based on multiple numerical ratings, as well as verbal descriptions.

## Project Structure
In this repository, you will find relevant files:
1. Dataset.zip - this file contains the .CSV data with the responses from the study participants
2. data_analysis.ipynb - here you will find the bulk of our computations, including the predictive models, clustering, and natural language processing
3. sessions_comparisson.ipynb - this file contains t-tests comparing 2 experimental sessions
4. sessions_scene_description.ipynb - here we implement code for grouping text based on relevant categories as well as extracting top 10 words
5. requirements.txt - this is the list of dependencies which should be installed with pip
6. gpt_exp1_scenes.txt - here we record the GPT4-generated descriptions of the scene data

### Environment

To run the code in this repository, you will need to first set up python virtual environment with the following commands:

```
python -m venv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
```

Next, 

## Usage
In order to successfully run the code in this repository, you will need to complete the following steps:

1. Clone the repository into your local machine
2. In the root folder of the repository, unzip the Dataset.zip file
2. After activating the environment and installing the dependencies, you can connect to the Jupyter Kernel and run the provided .ipynb notebooks
