# END-TO-END-DATA-SCIENCE-PROJECT-TASK-3

*COMPANY NAME: CODTECH IT SOLUTION

NAME:BANDIKARLA ACHYUTHVIVEK

INTERN ID:CT08DZ1113

DOMAIN NAME:DATA SCIENCE

DURATION:8 WEEKS

MENTOR: NEELA SANTOSH

Task Description :– End-to-End Data Science Project with Model Deployment (FastAPI)

Objective
To design, build, and deploy a complete machine learning pipeline — from data collection and preprocessing to model training, evaluation, and serving predictions via an API (FastAPI).

Scope & Workflow
Data Collection

Acquired dataset (e.g., CSV or API source).

Stored in a project /data directory.

Loaded using Pandas for preprocessing.

Data Preprocessing
Handled missing values using SimpleImputer.

Encoded categorical variables via OneHotEncoder.
Standardized numeric features with StandardScaler.
Combined steps in an Sklearn Pipeline for reproducibility.
Model Training

Used RandomForestClassifier for classification.

Split data into training & testing sets.

Evaluated using Accuracy, ROC-AUC, and Classification Report.

Artifact Management

Saved trained model as .joblib under /artifacts.

Version-controlled code for reproducibility.

Model Deployment (FastAPI)

Created an API with:

/health endpoint → returns API status.

/predict endpoint → accepts JSON input, returns prediction & probability.

Loaded model artifact at API startup.

Testing

Verified training metrics (Accuracy: 95.61%, ROC-AUC: 99.39%).

Smoke-tested API endpoints.

Deployment Readiness

Added Dockerfile for containerization.

Configured project for local or cloud deployment (Heroku, AWS, etc.).

Deliverables
Full source code (training script, preprocessing pipeline, FastAPI app, Dockerfile).

Trained model artifact (model.joblib).

API ready for deployment (can be tested locally).

Documentation including setup, usage, and API examples.

Key Output Example:-

✅ Training complete
🎯 Test Accuracy: 0.9649
🧠 Test ROC AUC: 0.9956

📊 Classification Report:
               precision    recall  f1-score   support

           0       0.96      0.96      0.96        43
           1       0.97      0.97      0.97        71

    accuracy                           0.96       114
   macro avg       0.96      0.96      0.96       114
weighted avg       0.96      0.96      0.96       114


✅ Model Performance:
Accuracy: 96.49%
ROC-AUC: 0.9953

https://github.com/siva333-png/END-TO-END-DATA-SCIENCE-PROJECT-TASK-3/issues/1#issue-3309902625


















