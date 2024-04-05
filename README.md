Data Science Salary Prediction

About the Dataset

•	Dataset: Data Scientist Salary US Glassdoor

•	Description: This dataset was created by scraping job postings related to the position of 'Data Scientist' from Glassdoor in the USA. It contains columns such as Job title, Salary Estimate, Job Description, Rating, Company, Location, Company Headquarters, Company Size, Company Founded Date, Type of Ownership, Industry, Sector, Revenue, and Competitors.

•	Objective: Implement a deep learning algorithm to construct a salary prediction model for jobs related to data science.

Approach

1.	Data Cleaning: Handled missing values by replacing them with placeholder variables.
	
2.	Feature Engineering and Selection: Ensured the model was fed relevant data for precise prediction.
	
3.	EDA Analysis: Employed advanced data visualization techniques such as Seaborn and Matplotlib to communicate meaningful insights effectively.
	
4.	Encoding Categorical Columns
   
5.	Splitting Dataset: Split the dataset into training and testing sets.
	
6.	Model Development:
	
o	Started with an initial model and gradually improved model performance by:

	Adding early stopping.

	Using k-fold cross-validation.

	Simplifying the model by reducing layers.

	Simplifying the model by reducing neurons.

o	Visualized and analyzed model performance using TensorBoard, storing the result in the 'logs' file.

o	Stored the model metrics in a JSON file 'models_metrics.json'.

o	Compared model performance using a bar chart.

7. Tools and Libraries

o	Data Manipulation: Pandas, NumPy
	
o	Data Visualization: Matplotlib, Seaborn
	
o	Regular Expressions: re
	
o	Warning Management: Warnings
	
o	Machine Learning: TensorFlow, Keras

o	Model Building: Sequential, Dense

o	Metrics: RootMeanSquaredError

o	Callbacks: TensorBoard, EarlyStopping

o	Model Evaluation: Sklearn
	
o	Data Splitting: train_test_split

o	Data Standardization: StandardScaler

o	Cross-Validation: KFold

o	Other: JSON (for storing model metrics)

	
8. Documents
•	Dataset: data_science_salary_2021.csv

•	Jupyter Notebook for Coding: data_science_salary_prediction.ipynb

•	Model Storing: logs file

•	Models Metric Storing: model_metrics.json

Conclusion

The model with reduced layers (2_ES_CV5_model) stood out as the best among all the models developed, exhibiting fewer overfitting problems. To further optimize the model, additional methods to reduce overfitting, such as feature selection and feature engineering, will be explored.





