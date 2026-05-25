# Applied Data Science Capstone ProjectOverview

Welcome to the Applied Data Science Capstone Project, where we predict the landing success of the SpaceX Falcon 9 first stage.SpaceX has revolutionized space travel by advertising Falcon 9 rocket launches at a competitive cost of $62 million, compared to other providers whose costs soar upwards of $165 million. This significant cost-saving is largely attributed to SpaceX's ability to reuse the first stage of the rocket. By accurately predicting first-stage landing success, we can better estimate launch costs—providing invaluable insights for companies bidding against SpaceX for rocket launches.Project ObjectivesThe project is structured into seven comprehensive modules, each designed to build on the previous one, culminating in a robust predictive 

Model:

1. SpaceX API Data Collection & WranglingData Collection: Initiated the project by making GET requests to the SpaceX API to gather historical launch data.Data Cleaning: Processed, formatted, and cleaned the raw JSON response to handle missing values and ensure consistency for downstream analysis.

2. Web Scraping Falcon 9 Launch RecordsBeautifulSoup Extraction: Extracted historical Falcon 9 launch records from Wikipedia using the BeautifulSoup library.Data Parsing: Parsed the raw HTML tables and converted them into a structured Pandas DataFrame.

3. Exploratory Data Analysis (EDA) & Training LabelsVisual Data Exploration: Conducted extensive EDA using Matplotlib and Seaborn to uncover underlying patterns, trends, and correlations.Label Creation: Defined and created the binary training labels (Success = 1, Failure = 0) required for supervised machine learning.

4. Database Integration with SQLIBM Db2 Loading: Loaded the prepared datasets into an IBM Db2 database to leverage SQL for structured querying.Insight Extraction: Formulated complex SQL queries to derive specific operational insights from the launch records.

5. Interactive Geospatial AnalysisFeature Engineering: Engineered key categorical and numerical features to boost model predictive power.Folium Mapping: Built interactive maps using Folium to visualize launch site locations, proximity to geographical markers, and localized success rates.

6. Visual Analytics with Plotly DashDashboard Development: Developed a real-time interactive web application using Plotly Dash.Dynamic Components: Implemented dropdown menus and range sliders to filter landing success pie charts and payload-vs-launch scatter plots dynamically.

7. Predictive Machine Learning ModelsPreprocessing: Standardized features using StandardScaler and split the data into training and test sets.Classification Modeling: Evaluated multiple algorithms, including Logistic Regression, Support Vector Machines (SVM), Decision Trees, and K-Nearest Neighbors (KNN).Hyperparameter Tuning: Utilized GridSearchCV to optimize hyperparameters for each model.Results & EvaluationThe predictive models yielded the following accuracy scores on the test set:Classification ModelTest Set AccuracyDecision Tree Classifier0.9444 (Best Performer)Support Vector Machine (SVM)0.8333K-Nearest Neighbors (KNN)0.8333Logistic Regression0.8333Note: The Decision Tree Classifier achieved the highest predictive accuracy on the test data, making it the optimal model for this deployment scenario.ConclusionThrough systematic data collection, rigorous feature engineering, geospatial mapping, and machine learning optimization, this project successfully built a workflow capable of predicting Falcon 9 first-stage landing outcomes. These predictive insights directly translate into actionable business intelligence for estimating commercial launch costs and analyzing competitive positioning in the aerospace market.


Acknowledgments
IBM: For designing the curriculum, datasets, and learning framework.
Coursera: For hosting the platform and facilitating the Data Science Professional Certificate series.

🚀 Explore the RepositoryFeel free to dive into the Jupyter notebooks to review the complete data pipelines, statistical insights, and deployment code. Whether you're a data science enthusiast, an aerospace hobbyist, or a professional looking into predictive modeling workflows, your feedback and suggestions are highly welcome!
