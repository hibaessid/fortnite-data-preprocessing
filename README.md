# Fortnite Data Preprocessing Notebook

This repository contains a Jupyter Notebook designed as a tutorial for the first session of our IEEE CIS chapter. The purpose of the notebook is to teach new students how to handle and preprocess data using Python and Pandas.

The tutorial includes the following steps:
- Loading and exploring the dataset
- Handling missing values and duplicates
- Transforming categorical columns
- Normalizing numerical columns using Min-Max Scaling
- Encoding and discretizing data as needed

## Dataset

The dataset used in this notebook is called **Fortnite Statistics**, and it is a collection of 88 end game Fortnite statistics, including:
- Rank placed, eliminations, assists, revives
- Accuracy, hits, headshots, distance traveled
- Materials gathered, materials used
- Damage taken, damage to players and structures
- Time of day, date, and mental state

You can download the Fortnite dataset from Kaggle using the following link:
[Download Fortnite dataset from Kaggle](https://www.kaggle.com/datasets/joebeachcapital/fortnite-statistics)

Please make sure to download and place the dataset in the appropriate location to run the notebook smoothly.

## Requirements

To run this notebook, you'll need the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`

You can install them using:

```bash
pip install pandas numpy scikit-learn
