# Data_Analysis
A comprehensive code that accomplishes several tasks related to data preprocessing, text classification using a Logistic Regression model, model evaluation, and saving/loading the model and TF-IDF vectorizer. Here's the summary 

**Data Preprocessing:**
- Loaded a dataset from a CSV file and performed initial data exploration.
- Handled missing data by removing rows with missing values.
- Checked for and removed duplicate rows.
- Performed text cleaning and normalization, converting text to lowercase and removing punctuation.
- one-hot encoded the 'Ticket Type' column.

**Text Preprocessing and NLP:**
- Tokenized text by splitting it into words.
- Removed stopwords using NLTK.
- Applied TF-IDF vectorization to 'Ticket Subject' and 'Ticket Description' columns.
- Split the dataset into training and testing sets.

**Text Classification:**
- Trained a Logistic Regression model to classify tickets based on 'Ticket Description' and 'Ticket Priority.'
- Made predictions on the test set and evaluated the model using accuracy and a classification report.

**Data Visualization:**
- Created bar charts to visualize the distribution of 'Ticket Priority' and the histogram of 'Customer Age.'
- Created a scatter plot to examine the relationship between 'Customer Age' and 'Customer Satisfaction Rating.'

**Statistical Analysis:**
- Performed a t-test on sample data.

**Saving and Loading the Model:**
- Saved the trained model using joblib.

**Deployment of Pre-trained Model:**
- Loaded the pre-trained model.
- Prepared new data for prediction and used the loaded model and TF-IDF vectorizer to make predictions on new data.

The code covers a wide range of tasks related to data preprocessing, NLP, classification, data visualization, and even statistical analysis. 

**Datasets Used:**
1)Customer Support Tickets Dataset.csv
2)Sample.csv (from Twitter Sentiment Analysis Dataset)

**Output:**
output(1).xlsx

**Model Saved Name:**
"Ticket_Priority_Classification_Model.pkl" saved as "your_model"(for temporary

**TF-IDF Vectorization Name:**
"TF_IDF_Vectorizer.pkl"
