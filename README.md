# Data Analytics Portfolio

Welcome to my GitHub repository. I am Ashitha, a dedicated and analytical-minded individual with a passion for extracting insights from complex datasets. As an aspiring data analyst, I bring a blend of technical expertise and strategic thinking to the table. With proficiency in programming languages such as Python and R, along with experience in data manipulation, statistical analysis, and machine learning techniques, I'm committed to delivering robust and impactful solutions. This repository serves as a showcase of my data projects, where each endeavor reflects my commitment to precision, innovation, and continuous learning.


**PROJECT 1**

**Sales Analysis Project: Optimizing Customer Engagement and Product Strategy**

**Introduction:**

  Welcome to my sales analysis project! In this project, I focused on analyzing sales data to optimize customer engagement and improve product strategy. Through comprehensive data 
  analysis and exploration, I aimed to gain insights into customer preferences, purchasing behavior, and the effectiveness of marketing efforts.

**Project Overview:**

This project involved merging 12 data files into a single .csv file and performing extensive data cleaning and exploration. 
The primary objectives included:
   -  Understanding customer preferences by analyzing product pairing trends.
   -  Identifying the optimal timing for advertisements to maximize customer engagement.
   -  Investigating factors influencing product preferences and purchase decisions.


**Data Consolidation:**

-  Merged 12 separate data files into a single .csv file for comprehensive analysis.

**Data Cleaning:**

-  Conducted thorough data cleaning to address missing values, duplicates, and inconsistencies.
-  Standardized data formats and resolved any discrepancies to ensure accurate analysis.

**Customer Preferences Analysis:**

-  Analyzed product pairing trends to understand which products customers prefer buying together.
-  Utilized association rule mining techniques to identify frequent itemsets and association rules.
-  Extracted insights to optimize product bundling strategies and enhance cross-selling opportunities.

**Advertisement Timing Analysis:**

-  Investigated the timing of customer interactions with advertisements for various products.
-  Utilized time-series analysis techniques to identify peak engagement periods.
-  Proposed strategies for scheduling advertisements at optimal times to maximize customer response rates.

**Product Preference Analysis:**

-  Explored factors influencing customers' preferences for specific products over others.
-  Conducted sentiment analysis on customer reviews to gauge product satisfaction levels.
-  Derived actionable insights to improve product features, pricing, and marketing strategies.

**Results and Insights:**

-  Identified popular product combinations and recommended bundling strategies to increase sales.
-  Determined peak advertisement times and proposed scheduling strategies for enhanced customer engagement.
-  Uncovered factors driving product preferences and provided recommendations for product enhancements.

**Technical Details:**

-  Programming Languages: Python
-  Libraries: Pandas, NumPy, Matplotlib, Seaborn
-  Tools: Jupyter Notebook
   
**Visualizations:**

-  Included various visualizations such as bar charts, line plots, and heatmaps to illustrate key findings.

**Conclusion:**

   In conclusion, this sales analysis project provided valuable insights into customer behavior and preferences, enabling data-driven decision-making to optimize product strategy and 
   marketing efforts. By leveraging advanced analytics techniques, we can enhance customer engagement, drive sales growth, and achieve sustainable business success.

---
**PROJECT 2**

**Data-Driven Customer Segmentation for Targeted Marketing Using K-Means Clustering**

The goal of this project is to understand the target customer base for the marketing team to better plan their strategies. By identifying the most important customer groups based on demographic and behavioral criteria such as age, gender, income, and mall shopping score, we aim to provide actionable insights for market segmentation. This will allow the marketing team to tailor their activities and improve customer engagement and satisfaction.

**Objective**
**Market Segmentation**

The primary objective of this project is to divide the mall's target market into approachable and meaningful segments. By creating subsets of the market based on demographic and behavioral criteria, we can better understand and target specific groups for marketing activities. This process involves:

-  Demographic Segmentation: Analyzing age, gender, and income to identify key customer segments.
-  Behavioral Segmentation: Using the mall shopping score to group customers based on their shopping behavior.

**Data Collection and Preprocessing**

The first step involves collecting and preprocessing the customer data. This includes handling missing values, normalizing numerical features, and encoding categorical variables.
-  Load the raw dataset.
-  Handle missing values and outliers.
-  Normalize/standardize numerical features.
-  Encode categorical variables (e.g., gender).


**Exploratory Data Analysis (EDA)**

Exploratory Data Analysis is a crucial step to understand the underlying patterns and distributions in the data. It involves summarizing the main characteristics of the data and visualizing relationships between different variables.
-  Descriptive Statistics: Calculate mean, median, mode, standard deviation, etc., for numerical features.
-  Distribution Analysis: Visualize the distribution of age, income, and mall shopping scores.
-  Correlation Analysis: Analyze correlations between different features using heatmaps.
-  Pairwise Relationships: Use pair plots to explore relationships between multiple variables.
 
**Univariate Clustering**

Univariate clustering involves performing K-Means clustering on a single feature to identify clusters based on that feature alone.
-  Select a single feature (e.g., annual income).
-  Perform K-Means clustering.
-  Visualize the clusters using histograms or scatter plots.
-  Interpret the clusters.

**Bivariate Clustering**

Bivariate clustering involves performing K-Means clustering on two features simultaneously to explore how they interact to form distinct customer groups.
-  Select two features (e.g., annual income and mall shopping score).
-  Perform K-Means clustering.
-  Visualize the clusters using scatter plots.
-  Interpret the clusters.

**Multivariate Clustering**

Multivariate clustering involves using multiple features for clustering to capture a more comprehensive view of customer behavior and demographics.
-  Select multiple features (e.g., age, gender, annual income, mall shopping score).
-  Perform K-Means clustering.
-  Use dimensionality reduction techniques (e.g., PCA) for visualization if necessary.
-  Visualize the clusters using scatter plots or 3D plots.
-  Interpret the clusters.
 
**Visualization and Interpretation**

Visualization and interpretation of the clustering results are essential to communicate the findings effectively. This includes creating detailed visualizations and summarizing insights.
-  Create scatter plots, bar charts, and other visualizations to display the clusters.
-  Summarize the findings in a detailed report.
-  Provide actionable insights based on the identified customer segments.

**Tools**

-  Seaborn: For creating scatter plots, pair plots, and bar charts.
-  Matplotlib: For basic visualizations and customization.
-  Pandas: For data manipulation and summary statistics.
-  Sklean: For normalizing numerical features in the dataset, ensuring consistent scales for accurate clustering analysis.
  
**Results**

The clustering analysis identifies Cluster 1 as the most lucrative segment, characterized by high-income individuals with a propensity for high spending, with approximately 54% being women shoppers. Tailored marketing campaigns should focus on personalized services, exclusive offers, and loyalty programs to retain and attract these high-value customers. Additionally, targeting popular items favored by this cluster can further enhance customer engagement and drive revenue growth. Cluster 2, comprising customers with lower income and spending score, presents an opportunity for targeted sales events to stimulate spending on popular items and increase overall sales volume. By leveraging these insights, the mall can optimize marketing strategies and improve overall business performance.

---
**PROJECT 3**

**Loan Approval Prediction**

**Objective**

The Loan Approval Prediction project aims to predict whether a loan application will be approved or not using various machine learning algorithms. By analyzing historical data of applicants, the model can assist financial institutions in automating and optimizing the loan approval process. This can help reduce the time taken for loan approval and minimize human errors in decision-making.

**Dataset**

The dataset used in this project consists of several features that capture the demographic and financial information of loan applicants. The key attributes include:

-  Loan_ID: Unique Loan ID
-  Gender: Gender of the applicant (Male/Female)
-  Married: Marital status of the applicant (Yes/No)
-  Dependents: Number of dependents (0, 1, 2, 3+)
-  Education: Education level of the applicant (Graduate/Not Graduate)
-  Self_Employed: Whether the applicant is self-employed (Yes/No)
-  ApplicantIncome: Income of the applicant
-  CoapplicantIncome: Income of the co-applicant
-  LoanAmount: Loan amount in thousands
-  Loan_Amount_Term: Term of loan in months
-  Credit_History: Credit history (1 = good, 0 = bad)
-  Property_Area: Property area (Urban/Semiurban/Rural)
-  Loan_Status: Loan approval status (Y = Yes, N = No)
  
**Preprocessing**

The dataset undergoes several preprocessing steps to prepare it for modeling:

-  Handling Missing Values: Imputation of missing values using strategies such as mean, median, or mode.
-  Encoding Categorical Variables: Converting categorical variables to numeric using techniques like label encoding.
-  Feature Scaling: Standardizing the numeric features to ensure they have a mean of 0 and a standard deviation of 1.

Encoding Categorical Variables: Convert categorical variables like Gender, Married, Dependents, Education, Self_Employed, and Property_Area into numerical values using label encoding.

Feature Scaling: Standardize the numeric features ApplicantIncome, CoapplicantIncome, LoanAmount, and Loan_Amount_Term to ensure they have a mean of 0 and a standard deviation of 1.

**Exploratory Data Analysis (EDA)**

EDA is performed to understand the distribution and relationships between variables. Key steps include:

-  Univariate Analysis: Analyzing the distribution of each feature using histograms and bar plots.
-  Bivariate Analysis: Examining relationships between pairs of features, such as ApplicantIncome vs. LoanAmount, using scatter plots and box plots.
-  Multivariate Analysis: Exploring interactions between multiple features and their combined effect on Loan_Status using heatmaps and pair plots.

**Modeling**

Various machine learning algorithms are implemented to predict loan approval status. The models used include:

-  Logistic Regression: Suitable for binary classification problems.
-  K-Nearest Neighbors (KNN): A non-parametric method based on feature similarity.
-  Support Vector Machine (SVM): Finds the optimal hyperplane to separate classes.
-  Decision Tree: A tree-based model that splits data based on feature values.
-  Random Forest: An ensemble of decision trees to improve accuracy and reduce overfitting.
-  Gradient Boosting: Sequentially builds models to correct errors of previous models.
-  Neural Network: A deep learning model that captures complex patterns.

**Model Evaluation**

The models are evaluated using various metrics:

-  Accuracy: The ratio of correctly predicted instances to total instances.
-  Precision: The ratio of true positive predictions to the total predicted positives.
-  Recall: The ratio of true positive predictions to the total actual positives.
-  F1-Score: The harmonic mean of precision and recall.
-  Confusion Matrix: A table to visualize the performance of the model in terms of true positives, true negatives, false positives, and false negatives.
-  Cross-Validation: Ensures the model generalizes well to unseen data by splitting the data into multiple training and validation sets.

**Results**

The performance of each model is compared, and the best-performing model is identified based on evaluation metrics. Typically, ensemble models like Random Forest and Gradient Boosting show superior performance due to their ability to handle complex data patterns.

**Conclusion**

The project demonstrates the application of various machine learning algorithms for predicting loan approval status. It highlights the importance of data preprocessing, exploratory data analysis, model selection, and evaluation in building a robust predictive model.

---
**PROJECT 4**

**Fake News Detection**

**Objective**

The primary objective of this project is to develop a machine learning model capable of accurately detecting fake news articles. With the proliferation of misinformation and false information online, it's essential to create a reliable system that can distinguish between genuine and fabricated news content. By leveraging machine learning algorithms, the project aims to achieve accurate detection of fake news using a dataset of labeled news articles.

**Dataset**

The project utilizes two datasets:

-  Fake.csv containing fake news articles.
-  True.csv containing true news articles.

**Data Preprocessing**

The data preprocessing steps include:

-  Merging the fake and true news datasets and adding a class label (0 for fake news, 1 for true news).
-  Dropping irrelevant columns (title, subject, date) to focus on the text content and class label.
-  Shuffling the merged dataset to ensure randomness.
-  Cleaning the text data by:
      Converting text to lowercase.
      Removing special characters, URLs, and HTML tags.
      Removing punctuation and numerical values.

**Model Training**

The cleaned text data is split into training and testing sets using an 75-25 split. The TfidfVectorizer is used to convert the text data into numerical features suitable for model training.

Four machine learning models are trained on the vectorized text data:

-  Logistic Regression
-  Decision Tree Classifier
-  Gradient Boosting Classifier
-  Random Forest Classifier

**Model Evaluation**

Each model is evaluated based on accuracy, precision, recall, and F1-score. The models are compared to determine the best performer.

**Results**
The performance of each model is evaluated based on accuracy, precision, recall, and F1-score. The results demonstrate that all models perform exceptionally well in distinguishing between fake and true news:

Logistic Regression:

-  Accuracy: 98.67%
-  Precision, Recall, and F1-score: 0.99

 Decision Tree:

-  Accuracy: 99.48%
-  Precision, Recall, and F1-score: 1.00 (for the true news class)

Gradient Boosting:

-  Accuracy: 99.51%
-  Precision and Recall: High values with an F1-score of 0.99

Random Forest:


-  Accuracy: 98.96%
-  Precision, Recall, and F1-score: 0.99

Ensemble models like Gradient Boosting and Decision Tree demonstrate superior performance due to their ability to handle complex data patterns effectively.

**Manual Testing**

A manual testing function is provided to predict the class of a given news article using all four trained models. This function cleans the input text, vectorizes it using the TfidfVectorizer, and outputs the predictions from each model.

**Conclusion**

This project successfully demonstrates the use of machine learning techniques to detect fake news with high accuracy. Ensemble models, in particular, show great promise in handling the complexities of text data, making them suitable for real-world applications in fake news detection.

---
**PROJECT 5**

**Student Result Analysis**

**Objective**

The Student Result Analysis project aims to analyze and understand the factors influencing students' academic performance based on the provided dataset containing information about students' scores and related demographic attributes. The dataset includes features such as gender, ethnic group, parental education level, lunch type, test preparation, parental marital status, practice of sports, number of siblings, transportation means, weekly study hours, and scores in mathematics, reading, and writing.

**Data Exploration and Preprocessing:**

-  Data Import: The project begins with importing the dataset using pandas, followed by an exploration of its structure and content.
-  Data Cleaning: Handling missing values and dropping unnecessary columns like the unnamed column to streamline the dataset for analysis.
-  Data Visualization: Visualizing gender distribution and exploring relationships between variables using count plots and heatmaps to gain insights into the data.

**Analysis and Insights:**

-  Gender Distribution: Analyzing the gender distribution to understand the representation of male and female students in the dataset.
-  Parental Education Impact: Investigating the impact of parental education on students' scores in mathematics, reading, and writing.
-  Parental Marital Status Analysis: Assessing the relationship between parental marital status and students' academic performance.
-  Outlier Detection: Identifying outliers in mathematics, reading, and writing scores using box plots to understand potential challenges faced by students in different subjects.
-  Ethnic Group Distribution: Exploring the distribution of students across ethnic groups and examining the influence of ethnic background on academic performance.

**Conclusion:**

The analysis reveals several insights regarding the factors influencing students' academic achievements. Parental education emerges as a significant predictor of student success, with higher levels of parental education correlating with better academic performance. Additionally, gender distribution, parental marital status, and ethnic background provide valuable context for understanding variations in student scores. The project concludes by highlighting the importance of addressing socio-economic factors and providing support to students from diverse backgrounds to ensure equitable educational outcomes.
<!---
ashithaninganagouda/ashithaninganagouda is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
