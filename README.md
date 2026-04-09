# CoviBot - COVID-19 Symptom Checker Chatbot 🦠
CoviBot is an intelligent chatbot application that assists users in assessing their COVID-19 risk based on reported symptoms and exposure factors. The system uses a Machine Learning model (Decision Tree Classifier) trained on a comprehensive COVID-19 symptoms dataset to predict whether a user is likely to have COVID-19.

The chatbot engages users through a natural conversation, asking about various symptoms (fever, cough, breathing problems) and exposure risks (travel history, contact with infected persons, large gatherings). Based on the user's responses, the model provides a prediction and recommends appropriate actions.

# Objectives 🎯
- **Data Analysis & Preprocessing:** Load and clean COVID-19 symptom dataset
- **Model Development:** Train and evaluate multiple ML classifiers
- **Model Selection:** Choose the best-performing model based on accuracy and speed
- **Chatbot Implementation:** Build an interactive GUI chatbot using Tkinter
- **Natural Language Processing:** Process user inputs using tokenization and stemming
- **Real-time Prediction:** Convert user responses to model-compatible format and predict

# Dataset 📊
The dataset contains 5,434 records with 21 features related to COVID-19 symptoms and risk factors:

**Features:**
- Symptoms: Breathing Problem, Fever, Dry Cough, Sore throat, Running Nose, Headache, Fatigue, Gastrointestinal issues
- Medical Conditions: Asthma, Chronic Lung Disease, Heart Disease, Diabetes, Hyper Tension
- Exposure Risks: Abroad travel, Contact with COVID Patient, Attended Large Gathering, Visited Public Exposed Places, Family working in Public Exposed Places
- Preventive Measures: Wearing Masks, Sanitization from Market (removed due to non-binary values)

**Target Variable:**
- COVID-19 (Yes/No)



#  Libraries Used 🛠️
- **Pandas:**	Data loading and manipulation
- **NumPy:**	Numerical operations
- **Scikit-learn:** OrdinalEncoder, train_test_split, DecisionTreeClassifier, metrics
- **LazyPredict:**	Automated model comparison
- **NLTK:**	Tokenization, stemming (PorterStemmer)
- **Tkinter:**	GUI development
- **Matplotlib:**	(Implicit, for potential visualizations)

# Key Learnings 🧠
- Feature selection is crucial - removing non-binary columns improved model quality
- Stratified splitting ensures representative class distribution in train/test sets
- LazyPredict dramatically speeds up model comparison (evaluates 23 models automatically)
- NLP preprocessing (tokenization, stemming) makes the chatbot robust to input variations
- Decision Trees are excellent for medical screening due to interpretability and speed
- Tkinter provides a simple yet effective GUI for chatbot deployment

 # License 📝
  This project is for educational purposes as part of a Master's lab assignment.

# Contact ✉️
 • **Email:** wissambadia4@gmail.com
 • **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214)  

