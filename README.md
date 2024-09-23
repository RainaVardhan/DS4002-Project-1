# DS4002-Project-1
## Software and platform
For the project, we used Python and the additional operator, joblib, numpy, pandas, scikit-learn, and matplotlib libraries. Each of our group members used Mac platforms.

## Map of documentation
In the DATA folder, there is course_data_clean.csv, which is a cleaned CSV file of our dataset. There is also stopwords copy.txt, which contains all the stopwords we used for topic modeling. In the SCRIPTS folder, there is DS 4002 Project 1.ipynb, which includes all of our source code for loading and cleaning the data, as well as topic modeling. In the OUTPUT folder, there are plots that were produced from initial EDA of our dataset.

## Instructions for reproducing results
To reproduce the results of this study, follow the steps outlined below:

1. Download the dataset: Start by downloading the course_data_clean.csv file from the following Kaggle dataset link: https://www.kaggle.com/datasets/anthonysusevski/course-reviews-university-of-waterloo. Please make sure you have access to the dataset by signing in to Kaggle and accepting the dataset's terms and conditions if necessary.
2. Set up your Python environment: Ensure you have Python 3.x installed, along with the necessary libraries (pandas, numpy, sklearn, matplotlib, seaborn, etc.). If using Google Colab, these libraries are pre-installed, but in other environments, you may need to run the following command to install them:pip install pandas numpy scikit-learn matplotlib seaborn
3. Open Google Colab: Go to Google Colab and sign in using your Google account.
4. Clone the repository and open the notebook: Open the DS 4002 Project 1.ipynb notebook, located in the SCRIPTS folder of the DS4002-Project-1 repository. To access it, clone the repository by writing the command !git clone https://github.com/RainaVardhan/DS4002-Project-1.git at the start of the script. This command will clone the entire repository with the course_data_clean.csv and stopwords copy.txt files. 
5. Run the notebook: After uploading the notebook and loading the dataset, go to the navigation bar in Colab, click on Runtime, and select Run all to execute all cells. This will run the entire analysis pipeline, including data preprocessing, model building, and result generation.
6. Review results: The notebook includes sections for data exploration, preprocessing, model training, and evaluation. Pay attention to any outputs, plots, or model performance metrics generated during the execution of the cells. For further analysis, you can modify or rerun specific cells to experiment with different models or parameters.
7. Save the results: Once the notebook finishes running, save the results (plots, metrics, etc.) by downloading them locally or saving them to your Google Drive.
