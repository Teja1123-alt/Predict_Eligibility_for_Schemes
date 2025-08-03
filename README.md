# Predict_Eligibility_for_Schemes
PREDICTING ELIGIBILITY FOR NSAP SCHEMES USING MACHINE LEARNING
CAPSTONE PROJECT

PROBLEM STATEMENT
The National Social Assistance Program (NSAP) is a key welfare program in India that offers financial support to elderly individuals, widows, and people with disabilities. Currently, verifying applications and assigning the correct scheme is done manually, which is time-consuming and error-prone. This may lead to delays or wrong scheme allocations.

Objective: Build a machine learning model that accurately predicts the suitable NSAP scheme for an applicant using demographic and socio-economic data.

PROPOSED SOLUTION
A multi-class classification model will be developed using IBM Cloud Watson Studio. It will take input data such as age, income, and gender, and predict the most suitable NSAP scheme.

Steps:

Data Collection:

Gather NSAP dataset (scheme codes, benefits, personal info) from AI Kosh and store it in IBM Cloud Object Storage.

Project Creation:

Create a Watson Studio project to manage datasets and models.

Model Training:

Use AutoAI or Python notebook for training. The model will learn from patterns in the data.

Evaluation:

Assess accuracy, confusion matrix, and feature importance. Tune if necessary.

Deployment:

Deploy the model using IBM Watson Machine Learning and create a REST API.

Prediction & Testing:

Input applicant data in JSON format via API and get the predicted scheme.

SYSTEM APPROACH
System Requirements:

Cloud Platform: IBM Cloud Lite

Storage: IBM Cloud Object Storage

Environment: IBM Watsonx.ai Studio

AutoML: IBM AutoAI

Libraries:

Language: Python 3

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn

Deployment: IBM Watson Machine Learning

Input: JSON

Output: REST API

WOW FACTORS
AI-Driven Predictions in Seconds
Manual checks take hours—AI gives real-time results.

Cloud-Based & API Enabled
Easily integrated into government systems.

Ready for Real-World Use
REST API can be used directly in government offices or CSCs.

END USERS
Government Officers

Village/Ward Secretaries

NGOs and Social Workers

Welfare Departments

Pension Applicants

ALGORITHM & DEPLOYMENT
Algorithm Used:

Random Forest

Logistic Regression

AutoAI typically selects one of these based on accuracy and F1-score.

Data Input:

Dataset contains applicant demographic and socio-economic details in CSV format.

Training & Prediction:

Model trained on IBM Watson Studio.

Deployed via Watson Machine Learning as a REST API.

RESULTS
(No specific data shown, likely in graphical or tabular form in the PDF.)

CONCLUSION
The project proves that AI and IBM Cloud can automate the eligibility process for NSAP schemes. It provides fast, reliable classification, ensuring deserving people receive benefits on time.

Benefits:

Practical and scalable via REST API

Increases efficiency and fairness in welfare distribution

FUTURE SCOPE
Real-time Data: Connect to government databases

Explainable AI: Use LIME or SHAP for transparency

Unstructured Data: Handle scanned forms, handwritten inputs

Model Retraining: Enable continuous learning

Integration: Deploy with government portals

Mobile App: For field workers

Fraud Detection: Add anomaly detection features

Multilingual Input, Expansion to Other Schemes, Periodic Updates

GITHUB LINK & REFERENCES
GitHub Link: (Not provided in the file)

IBM Cloud Lite:
🔗 https://cloud.ibm.com

IBM Watson Studio:
🔗 https://dataplatform.cloud.ibm.com

Scikit-learn:
🔗 https://scikit-learn.org/

NSAP Website:
🔗 https://nsap.nic.in/

IBM CERTIFICATIONS OBTAINED
Getting Started with Artificial Intelligence

Journey to Cloud: Envisioning Your Solution

Retrieval Augmented Generation with LangChain

