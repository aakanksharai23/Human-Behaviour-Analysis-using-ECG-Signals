Human Behaviour Data Analysis
Overview
This project provides a workflow for analyzing human activity data using machine learning methods. It downloads a public mobile health dataset from Kaggle, preprocesses the data, balances it, and performs exploratory data analysis in preparation for modeling. The script is compatible with Jupyter or Colab environments and utilizes popular Python data science and deep learning libraries.
Features
•	Downloads the mobile-health dataset from Kaggle using kagglehub
•	Loads and displays the dataset
•	Downsamples the majority class for better balance in activity classification
•	Explores feature ranges for outlier analysis
•	Prepared for deep learning modeling with TensorFlow and Keras (setup shown)
Requirements
•	Python 3.6 or newer
•	Colab or Jupyter environment recommended
•	Libraries:
o	numpy
o	pandas
o	seaborn
o	matplotlib
o	tensorflow
o	keras
o	kagglehub
o	scikit-learn
Install required packages with:
pip install numpy pandas seaborn matplotlib tensorflow keras kagglehub scikit-learn

Usage
1.	Run the script in a local Jupyter notebook or Google Colab.
2.	The script will automatically:
o	Download the mobile-health dataset from Kaggle using kagglehub
o	Load the CSV file
o	Downsample the majority activity class (for class balance)
o	Print and display feature ranges to help investigate outliers
File Structure
•	human_behaviour.py: Main code file for dataset download, preparation, and basic analysis.
Dataset
•	Dataset: gaurav2022/mobile-health on Kaggle
•	The script fetches data automatically with kagglehub.
Example Output
•	Path to downloaded dataset files
•	Display of the loaded DataFrame
•	Value counts for the balanced Activity column
•	Printed feature ranges for initial outlier detection
Next Steps
•	Expand with modeling and evaluation (e.g., adding deep learning code using Keras/TensorFlow)
•	Visualize data distributions with seaborn/matplotlib
•	Perform feature engineering and hyperparameter tuning
License
This script is provided for educational and research purposes. Please check dataset source license for usage restrictions.
Author
If this is a collaboration, add GitHub handles or names here.
 
 

