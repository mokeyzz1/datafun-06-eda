# datafun-06-eda

## Project Overview

- This project involves setting up an environment for exploratory data analysis (EDA) using Python. The project includes creating a virtual environment, installing necessary external packages, and managing dependencies via a requirements.txt file. This repository is part of the data analysis workflow and focuses on working with data using Jupyter notebooks and Python packages such as numpy, pandas, matplotlib, seaborn, and more.

## Setup Instructions

1. Clone the Repository
Clone the repository from GitHub to your local machine:
git clone https://github.com/mokeyzz1/datafun-06-eda

2. Set Up a Virtual Environment
In the project directory, create and activate a virtual environment:
# Create virtual environment
py -m venv .venv
# Activate virtual environment (Mac/Linux)
source .venv/bin/activate

3. Install Dependencies
After activating the virtual environment, install the required packages:
python -m pip install -r requirements.txt

## Git Workflow

For working with the repository, use the following commands:

Stage changes:
````
git add .
git commit -m "Describe your changes"
git push -u origin main
````

## Dataset Overview

The dataset contains information about movies and TV shows, including their titles, years of release, certificates, durations, genres, ratings, descriptions, stars, and votes.

- **Total Records**: 9957
- **Features**:
  - **Title**: Name of the movie or TV show
  - **Year**: Year of release
  - **Certificate**: Age rating
  - **Duration**: Running time
  - **Genre**: Genre(s) of the movie
  - **Rating**: IMDb rating
  - **Description**: Summary of the movie
  - **Stars**: Main actors and actresses
  - **Votes**: Number of user votes

**Link to Dataset**: [IMDb Dataset on Kaggle](https://www.kaggle.com/code/payamamanat/imdb-movies#Dataset-Description)
*** data set- (/Users/mk/Downloads/IMBD.csv)

