# Drug Review Sentiment Analysis Using Natural Language Processing

## Project Summary

This project applies Natural Language Processing (NLP) techniques to analyze patient drug reviews and evaluate drug effectiveness using real-world healthcare data. Multiple NLP approaches, including VADER sentiment analysis, BERT transformer models, TF-IDF with Logistic Regression, and biomedical Named Entity Recognition (SciSpaCy), were implemented to classify patient sentiment, extract medical entities, and identify patterns related to medication benefits and side effects.

The project demonstrates the application of machine learning and NLP techniques in healthcare analytics to transform unstructured patient feedback into meaningful insights that can support evidence-based decision-making.

## Project Overview

Patient-generated drug reviews provide valuable real-world evidence about medication effectiveness, treatment experiences, and adverse effects. However, these reviews are typically stored as unstructured text, making large-scale analysis challenging.

In this project, Natural Language Processing (NLP) techniques were applied to transform unstructured patient reviews into structured insights. The analysis included sentiment classification, biomedical named entity recognition, and machine learning models to evaluate drug effectiveness and identify common themes related to medication benefits and side effects.

The project demonstrates how NLP can support healthcare analytics by extracting meaningful information from patient feedback, helping healthcare professionals, researchers, and pharmaceutical organizations better understand real-world treatment outcomes.

  ## Business Impact

Patient-generated drug reviews contain valuable real-world evidence about medication effectiveness, treatment experiences, and adverse effects. However, manually analyzing thousands of unstructured reviews is time-consuming and difficult.

This project demonstrates how Natural Language Processing (NLP) can transform unstructured patient feedback into actionable healthcare insights by:

- Automatically classifying patient sentiment toward medications.
- Identifying common medication benefits and adverse effects.
- Extracting clinically relevant entities such as drug names and medical conditions.
- Supporting evidence-based healthcare research through large-scale text analysis.
- Demonstrating how machine learning and NLP can improve healthcare decision-making using real-world patient data.

## Research Objectives

- Analyze patient drug reviews to evaluate perceived drug effectiveness.
- Classify patient sentiment as positive, negative, or neutral using VADER and BERT.
- Extract biomedical entities such as drug names, medical conditions, and symptoms using SciSpaCy.
- Predict drug effectiveness using TF-IDF with Logistic Regression and transformer-based language models.
- Identify common patterns in medication benefits, adverse effects, and patient experiences through NLP techniques.

- ## Dataset

The analysis was performed using the **Drug Review Dataset (DrugLib.com)** obtained from the **UCI Machine Learning Repository**. The dataset contains real-world patient reviews describing medication experiences, treatment effectiveness, side effects, and satisfaction ratings.

**Dataset Characteristics**

- Source: UCI Machine Learning Repository (DrugLib.com)
- Approximately 4,150 patient reviews
- Structured and unstructured healthcare data
- Publicly available dataset for research purposes

**Key Variables**

- Drug Name
- Medical Condition
- Patient Review
- Effectiveness Rating
- Side Effects
- Overall Satisfaction Rating

  ## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- NLTK
- VADER Sentiment Analyzer
- Hugging Face Transformers (BERT)
- SciSpaCy
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib
- Seaborn

  ## Methodology

The project followed the following Natural Language Processing workflow:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Text Preprocessing
5. VADER Sentiment Analysis
6. BERT Sentiment Classification
7. Named Entity Recognition using SciSpaCy
8. TF-IDF Feature Extraction
9. Logistic Regression Classification
10. Performance Evaluation
11. Result Interpretation

    ## Project Workflow

```text
Drug Review Dataset
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Text Preprocessing
(Tokenization, Stopword Removal, Lemmatization)
        │
        ▼
Sentiment Analysis
(VADER & BERT)
        │
        ▼
Named Entity Recognition
(SciSpaCy)
        │
        ▼
Feature Extraction
(TF-IDF)
        │
        ▼
Machine Learning
(Logistic Regression)
        │
        ▼
Model Evaluation & Insights
```

## Key Results

- Successfully classified patient reviews into positive, negative, and neutral sentiments using VADER and BERT.
- Identified stronger negative sentiment within side-effect reviews compared to medication benefit reviews.
- Extracted biomedical entities including drug names, medical conditions, and symptoms using SciSpaCy.
- Evaluated drug effectiveness prediction using TF-IDF with Logistic Regression and transformer-based language models.
- Demonstrated the value of Natural Language Processing for transforming unstructured healthcare text into actionable insights.

  ## Skills Demonstrated

- Natural Language Processing (NLP)
- Sentiment Analysis
- Healthcare Data Analytics
- Machine Learning
- Text Classification
- Named Entity Recognition (NER)
- Data Cleaning and Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Model Evaluation
- Data Visualization
- Python Programming

  ## Repository Contents

| File | Description |
|------|-------------|
| `README.md` | Project overview and documentation |
| `NLP_Final_Project.ipynb` | Complete project notebook containing data preprocessing, NLP pipeline, and model implementation |
| `Drug_Review_Dataset.csv` | Drug review dataset used for analysis |
| `Project_Report.pdf` | Detailed project report describing methodology, results, and discussion |
| `images/` | Project screenshots, workflow diagrams, and visualizations |

## How to Run the Project

1. Clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Load the Drug Review Dataset.
5. Run the notebook cells sequentially.
6. Review the generated visualizations, sentiment analysis results, and model performance.

   ## Future Improvements

- Fine-tune transformer-based language models for improved sentiment classification.
- Evaluate additional deep learning architectures for effectiveness prediction.
- Apply topic modeling to discover emerging themes in patient reviews.
- Develop an interactive dashboard to visualize NLP results.
- Expand the analysis using larger real-world healthcare datasets.

  ## References

- UCI Machine Learning Repository – Drug Review Dataset (DrugLib.com)
- NLTK Documentation
- Hugging Face Transformers
- SciSpaCy Documentation
- Scikit-learn Documentation

  
