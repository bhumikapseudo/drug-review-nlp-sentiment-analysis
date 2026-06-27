# Drug Review Sentiment Analysis Using Natural Language Processing

## Project Summary

This project applies Natural Language Processing (NLP) techniques to analyze patient drug reviews and evaluate drug effectiveness using real-world healthcare data. The analysis combines rule-based and transformer-based sentiment analysis with machine learning models to classify patient feedback and identify patterns related to medication benefits, side effects, and overall treatment experience.

The project demonstrates how unstructured healthcare text can be transformed into meaningful insights that support healthcare analytics and evidence-based decision-making.

## Project Overview

Patient-generated drug reviews provide valuable real-world evidence about medication effectiveness, treatment experiences, and adverse effects. However, these reviews are typically stored as unstructured text, making large-scale analysis challenging.

In this project, Natural Language Processing (NLP) techniques were applied to transform unstructured patient reviews into structured insights. The analysis included sentiment classification, biomedical named entity recognition, and machine learning models to evaluate drug effectiveness and identify common themes related to medication benefits and side effects.

The project demonstrates how NLP can support healthcare analytics by extracting meaningful information from patient feedback, helping healthcare professionals, researchers, and pharmaceutical organizations better understand real-world treatment outcomes.

## Business Impact

Patient-generated drug reviews contain valuable real-world evidence about medication effectiveness, treatment experiences, and adverse effects. However, manually reviewing thousands of patient comments is time-consuming and difficult.

This project demonstrates how Natural Language Processing can:

- Automatically classify patient sentiment toward medications.
- Identify trends in medication benefits and side effects.
- Support healthcare research using real-world patient feedback.
- Transform unstructured healthcare text into actionable insights.

## Research Objectives

- Analyze patient drug reviews using Natural Language Processing.
- Compare rule-based (VADER) and transformer-based (BERT) sentiment analysis.
- Predict patient sentiment from review text.
- Evaluate drug effectiveness using machine learning techniques.
- Explore biomedical text processing techniques for healthcare analytics.
  
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
- Matplotlib

 ## Methodology

The project followed the following Natural Language Processing workflow:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Text Preprocessing
5. VADER Sentiment Analysis
6. BERT Sentiment Classification
7. TF-IDF Feature Extraction
8. Logistic Regression Classification
9. Performance Evaluation
10. Result Interpretation

   ## Project Workflow
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
VADER Sentiment Analysis
(Rule-Based Sentiment Classification)
        │
        ▼
BERT Sentiment Classification
(Transformer-Based NLP)
        │
        ▼
Sentiment Comparison & Analysis
        │
        ▼
Healthcare Insights
```

## Key Results

- Classified patient reviews using VADER and BERT sentiment analysis.
- Compared rule-based and transformer-based NLP approaches.
- Identified stronger negative sentiment in side-effect reviews.
- Demonstrated how NLP can support healthcare analytics using patient-generated text.
  
 ## Skills Demonstrated

- Natural Language Processing (NLP)
- Sentiment Analysis
- Machine Learning
- Healthcare Data Analytics
- Text Preprocessing
- Transformer Models (BERT)
- Data Cleaning
- Exploratory Data Analysis
- Python Programming
  ## Repository Contents

| File | Description |
|------|-------------|
| `README.md` | Project overview and documentation |
| `NLP__Project_g.ipynb` | Complete project notebook containing data preprocessing, NLP pipeline, and model implementation |
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
  
