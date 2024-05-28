# TASK - 4

### SPAM SMS DETECTION MODEL

#### Overview
This project focuses on developing a robust model for detecting spam SMS messages using machine learning techniques. It involves loading and preprocessing a dataset containing SMS messages, performing exploratory data analysis (EDA), extracting features using TF-IDF vectorization, and training a Logistic Regression model. The model's performance is evaluated based on accuracy, precision, recall, and F1-score metrics.

#### 1. Load the Dataset
- Utilized Pandas to load the dataset from the provided ZIP file.
- Ignored warnings to maintain code clarity.
- Extracted the contents of the ZIP file for data accessibility.

#### 2. Data Cleaning
- Investigated missing values in the dataset, primarily focusing on columns `Unnamed: 2`, `Unnamed: 3`, and `Unnamed: 4`.
- Filtered unnecessary columns and renamed the remaining ones for better readability.

#### 3. EDA and Data Visualization
- Explored the dataset's structure, confirming non-null counts and data types.
- Examined basic statistics and identified the most frequent message in each category.
- Visualized the distribution of spam and ham messages using a countplot.
- Analyzed the distribution of message lengths for both spam and ham messages.

#### 4. Preprocess the Data
- Preprocessed text data by converting to lowercase, removing punctuation, and digits.

#### 5. Feature Extraction using TF-IDF
- Employed TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to extract features from text data.
- Split the dataset into features (`X`) and labels (`y`).

#### 6. Split the Data into Training and Test Sets
- Segregated the data into training and testing sets using a 80:20 ratio.

#### 7. Evaluate Model
- Conducted hyperparameter tuning for Logistic Regression using GridSearchCV to optimize model performance.
- Determined the best parameters for the model.
- Made predictions on the test set and evaluated model accuracy using accuracy score, classification report, and confusion matrix heatmap.

#### Conclusion:
- The spam SMS detection model achieved an impressive accuracy of 97.67% on the test set.
- The model exhibited high precision (98%) and recall (85%) for detecting spam messages.
- With a weighted average F1-score of 0.98, the model demonstrates excellent overall performance.
- This model effectively filters unwanted messages, enhancing user experience and privacy.
- Further improvements could involve exploring ensemble methods or deep learning architectures for even better performance.
  
**Dataset and Code File:**
- Dataset: [Churn_Modelling](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Code File: [spam_sms_detection.ipynb]([/spam_sms_detection.ipynb](https://github.com/shravanichandane/CODSOFT_4/blob/main/CODSOFT_4.ipynb)) 

Feel free to explore the dataset and code file for more details!

#DataScience #MachineLearning #SpamDetection #DataAnalysis #Python #GitHubReadme
