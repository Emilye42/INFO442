#Rossmann Store Sales Data Research Project
Overview
This project, conducted by Group 5 for Drexel University's INFO442 course, focuses on analyzing the Rossmann Store Sales dataset. The primary objective is to derive insights and build predictive models to forecast sales for the Rossmann drug store chain.

Dataset
The dataset used for this project is sourced from Kaggle:
Rossmann Store Sales Dataset

#Dataset Description
The dataset contains historical sales data for Rossmann stores. Each row represents a specific store's sales data on a particular date. 
https://www.kaggle.com/code/uttam94/time-series-analysis-using-prophet

#Project Structure
The project is organized as follows:

data/: Contains the raw and processed data files.
notebooks/: Jupyter notebooks with exploratory data analysis (EDA), data cleaning, and model development.
src/: Python scripts for data processing, feature engineering, and model training.
reports/: Generated reports and visualizations.
README.md: Project overview and instructions.

#Getting Started
Prerequisites
Python 3.x
Jupyter Notebook
Required Python libraries:
pandas
numpy
scikit-learn
matplotlib
seaborn
Installation
Clone the repository:
bash
git clone https://github.com/Emilye42/INFO442-------------------

Navigate to the project directory:
bash
cd rossmann-sales

Install the required Python libraries:
bash
pip install -r requirements.txt

Usage
Data Preparation:

Download the dataset from Kaggle and place it in the data/raw directory.
Run the data cleaning and preprocessing script:
bash
python src/data_preprocessing.py

Exploratory Data Analysis (EDA):

Open and run the EDA notebook:
bash
jupyter notebook notebooks/eda.ipynb


Model Development:

Run the model training script:
bash
python src/model_training.py

Evaluation:

Evaluate the model performance using the evaluation notebook:
bash
jupyter notebook notebooks/evaluation.ipynb

Contributors
Group 5 Members(alphabetical):
EmilyYe
Jerry Li
Junkai Ge
Shenyang Dong

License
This project is licensed under the MIT License.

Acknowledgements
We would like to thank Kaggle for providing the dataset and the Drexel University INFO442 instructors for their guidance and support.








