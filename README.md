# DSC412-project

## Project Overview
Fantasy football is a game where participants create and manage a team using real NFL players, competing
weekly against others in a league. Players score Fantasy Points (FPS) based on real-life performance, with the
highest scorer winning the matchup. Participants set their starting lineup weekly by evaluating projected points
and past performances, but projections don’t always predict actual outcomes. Factors like location, weather, or
team advantage can affect a player's performance, yet there’s no easy way to account for them quantitatively.
**This project proposes developing a Machine Learning (ML) model to improve FPS projections and
support better player selection.**

## Project Proposal

Please see [DSC412_001_FA24_PR_amcheste.pdf](DSC412_001_FA24_PR_amcheste.pdf) for a detailed project proposal.

## Prerequisites
Make sure pip is at least version 24.2

`python -m pip install --upgrade pip`

Install the requirements using: python3 -m venv .venv

Activate the virtual env

Windows: `.\.venv\Scripts\activate`

Mac: `source ./.venv/bin/activate`

Linux: `source ./.venv/bin/activate`

Install the requirements

`python3 -m pip install -r ./requirements.txt`

## Data Collection

The data for this project has been collected from a combination of ESPN for historical player stats and yahoo for fantasy football points per game.
Please see https://github.com/amcheste/fball_data_collection for details on the data collection.  It should be noted that
since the data collection takes multiple hours the data has already been collected and stored in a object storage bucket for this project.  Therefore, there is no need to run the data collection project


## Data Preprocessing
Please see [01_preprocessing](notebooks/01_preprocessing.ipynb) for  data pre-processing.

## Data Analysis & Feature Engineering

Please see [02_feature_engineering](notebooks/02_feature_engineering.ipynb) for data analysis and feature engineering.

## Model Training

Please see [03_model_training](notebooks/03_model_training.ipynb) for data analysis and feature engineering.

