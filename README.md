# Zomato Bangalore Restaurants — EDA

This project contains a complete Exploratory Data Analysis (EDA) of the Zomato Bangalore Restaurants dataset. The notebooks explore dataset cleaning, feature engineering, visualizations, and insights about restaurants and dining patterns in Bangalore.

## Table of contents
- Project overview
- Dataset
- Notebooks
- How to run
- Project structure
- Key insights
- Requirements
- Contributing
- License
- Contact

## Project overview
This repository hosts Jupyter Notebooks that perform data cleaning, exploratory analysis, visualizations, and basic modeling where applicable to help understand factors affecting restaurants and ratings in Bangalore.

## Dataset
The analysis uses the Zomato Bangalore Restaurants dataset (CSV). If the dataset is not included in this repo, download it from the original source and place it in the `data/` directory (create one if needed).

## Notebooks
- EDA notebooks (main notebooks found in the repo root or notebooks/):
  - data_cleaning.ipynb — cleaning and preprocessing
  - exploratory_analysis.ipynb — main visualizations and EDA
  - additional_analysis.ipynb — extra plots and insights

(Adjust these names to match the actual notebook filenames in the repo.)

## How to run
1. Clone the repo:
   git clone https://github.com/krishna7602/zomato-eda.git
2. Create a virtual environment (recommended):
   python -m venv .venv
   source .venv/bin/activate  # macOS / Linux
   .venv\Scripts\activate     # Windows
3. Install dependencies:
   pip install -r requirements.txt
   (If no requirements.txt exists, install: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, jupyter)
4. Start Jupyter Notebook:
   jupyter notebook
5. Open the notebooks and run cells.

You can also open notebooks in Google Colab by uploading the notebook or using the GitHub > Open in Colab workflow.

## Project structure
- notebooks/ or root: Jupyter notebooks (.ipynb)
- data/: raw and processed datasets (not committed if large)
- README.md

## Key insights (examples)
- Distribution of ratings across cuisines and locations
- Relationship between pricing and ratings
- Popular cuisines and restaurant types in Bangalore
(Add actual insights from your notebooks.)

## Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, jupyter

Add a requirements.txt with exact versions if you want reproducible environments.

## Contributing
Contributions are welcome. Create an issue or submit a PR with improvements, additional analyses, or corrections.

## License
Add a license file (e.g., MIT) if you want to make the repo permissively licensed.

## Contact
krishna7602 — https://github.com/krishna7602
