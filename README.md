# College Feedback Classifier (NLP Project)

An AI-powered system that automatically classifies open-ended student feedback into meaningful categories using IBM watsonx foundation models and few-shot prompting.

---

## Problem

Educational institutions receive large volumes of student feedback.  
Manually reading and categorizing this feedback is:

- time-consuming  
- inconsistent  
- prone to oversight  

There is a need for an automated system that can structure feedback into actionable categories.

---

## Solution

This project uses **IBM watsonx.ai FLAN-T5 foundation model** with **few-shot prompting** to classify feedback into:

- Academics  
- Facilities  
- Administration  

The model understands natural language feedback and generates category predictions without traditional ML training.

---

## Tech Stack

- Python  
- Pandas  
- IBM watsonx.ai  
- IBM Watson Machine Learning SDK  
- FLAN-T5 Foundation Model  
- Jupyter Notebook  

---

## Workflow

Student Feedback CSV
↓
Load Data using Pandas
↓
Few-Shot Prompt Template
↓
FLAN-T5 Foundation Model
↓
Predicted Category
↓
Export Results to CSV


---

## Features

- NLP-based classification  
- Few-shot prompting (no training required)  
- Cloud integration with IBM watsonx  
- Automated CSV output generation  
- Easily adaptable to other domains  

---

## Project Structure

college-feedback-classifier/
│
├── notebook.ipynb
├── college_feedback_expanded.csv
├── college_feedback_with_predictions.csv
├── report.pdf
├── requirements.txt
└── README.md


---

## How to Run This Project

### 1. Clone repository
git clone https://github.com/JaswanthChintha/college-feedback-classifier.git
cd college-feedback-classifier


### 2. Install dependencies
pip install -r requirements.txt


### 3. Add IBM Cloud credentials
- Create IBM Cloud account  
- Generate API key  
- Enter API key when prompted  

### 4. Run the notebook
jupyter notebook

Open the notebook and run cells step-by-step.

### 5. Use your own dataset
Replace the dataset file with your own feedback CSV to classify new data.

---

## Output

- Model classifies feedback into categories  
- Predictions saved in CSV file  
- Structured insights generated from raw text  

---

## Example Use Cases

This project can be adapted for:

- product reviews  
- employee feedback analysis  
- customer support tickets  
- app reviews  
- survey responses  

---

## Results

- Automated feedback classification  
- Reduced manual effort  
- Structured insights for decision-making  

---

## Future Improvements

- Add evaluation metrics (accuracy, precision, recall)  
- Build Streamlit web app interface  
- Deploy as API  
- Extend categories beyond 3 classes  

---

## Author

Jaswanth  
B.Tech CSE – VIT AP University  

---


---

⭐ If you found this project useful, consider giving it a star on GitHub!
