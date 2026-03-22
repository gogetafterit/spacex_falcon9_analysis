Author: Santiago Manuel Pallares Bartolomé. 

IBM Data Science Capstone Project | 2026.

Project: SpaceX Falcon 9 Landing Prediction.

​Project Context:

SpaceX has disrupted the aerospace industry by making rocket launches significantly cheaper. This cost reduction is driven by the successful recovery and reuse of the Falcon 9 first-stage booster. The goal of this project was to identify the specific factors that lead to a successful landing and to build a classification model that predicts these outcomes with high reliability.

​The Analytical Roadmap:

​Data Acquisition | Integrated data from the SpaceX API and parsed mission details from Wikipedia via web scraping.

​Data Wrangling | Cleaned the dataset and engineered features to isolate variables like Payload Mass, Orbit Type, and Launch Site.

​Exploration | Used SQL and Python (Seaborn/Matplotlib) to identify success trends over time and across different mission profiles.

​Interactive Visualization | Built a Folium map to analyze launch site proximity to coastlines and a Plotly Dash dashboard for real-time mission filtering.

​Machine Learning | Evaluated Logistic Regression, SVM, KNN, and Decision Tree models using GridSearchCV for hyperparameter tuning.

​Key Findings:

​Consistency: All tested models converged at a test accuracy of 83.33%.

​Reliability: The final model achieved a 100% recall rate for successful landings, meaning it perfectly identified every actual success in the test set.

​Primary Influencers: Analysis confirms that the specific Orbit type and Payload weight are the strongest predictors of whether a booster will be recovered.

​Repository Navigation

​Notebooks: Contains the end-to-end Python code for data cleaning, EDA, and model training.

​Dashboard: The app.py file containing the interactive Dash application logic.

​Presentation: The final project report summarizing the technical and business insights.
