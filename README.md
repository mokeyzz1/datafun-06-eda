# datafun-06-eda

## Project Overview

- This project involves setting up an environment for exploratory data analysis (EDA) using Python. The project includes creating a virtual environment, installing necessary external packages, and managing dependencies via a requirements.txt file. This repository is part of the data analysis workflow and focuses on working with data using Jupyter notebooks and Python packages such as numpy, pandas, matplotlib, seaborn, and more.

## Repository Structure
- `datafun-06-eda/` - Root folder for the project.
  - `moses_eda.ipynb` - Jupyter Notebook containing the EDA.
  - `README.md` - Documentation for the project.
  - `.gitignore` - Specifies files and folders to be ignored by Git.
    - `requirements.txt` - File listing dependencies required for the project.
    - `venv/` - Virtual environment folder.



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

### Dataset Features
- **title**: Title of the movie.
- **year**: Year of release.
- **certificate**: Age rating.
- **duration**: Duration of the movie in minutes.
- **genre**: Genre of the movie.
- **rating**: IMDb rating.
- **description**: Brief description of the movie.
- **stars**: Main actors.
- **votes**: Number of votes received.

**Link to Dataset**: [IMDb Dataset on Kaggle](https://www.kaggle.com/code/payamamanat/imdb-movies#Dataset-Description)
*** data set- (data/IMBD.csv)

