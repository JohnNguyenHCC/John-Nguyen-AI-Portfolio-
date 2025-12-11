# NewsBot Intelligence System  
ITAI 2373 Midterm Project  
Author: John Nguyen  

## Overview  
This directory contains the midterm version of the NewsBot Intelligence System.  
This project applies core NLP techniques from Modules 1 through 8 to analyze and classify news articles.  
The system demonstrates a full pipeline from preprocessing to machine learning based classification with added insight extraction such as sentiment POS patterns and named entities.

## Key Features  
- Text preprocessing and normalization  
- TF IDF feature extraction  
- POS tagging and grammatical pattern checks  
- Syntax and dependency parsing  
- Named entity recognition  
- Sentiment analysis using VADER  
- Multi class classification  
- Visualization of category patterns  

## Files Included  
```
ITAI2373-NewsBot-Midterm/
│
├── NewsBot_Midterm.ipynb
├── README.md
└── bbc_news_clean_sample.csv
```

## How to Run  
1. Open the notebook in Google Colab  
2. Upload the full BBC dataset file if needed  
3. Run each cell in order  
4. The system will output preprocessing steps classification scores POS patterns sentiment results and entity extraction  

## System Workflow  
1. Load dataset  
2. Clean text and preprocess  
3. Extract TF IDF features  
4. Analyze POS and syntax patterns  
5. Extract entities  
6. Run sentiment analysis  
7. Train and evaluate multi class classifiers  

## Skills Demonstrated  
- Handling raw text  
- Building ML ready text features  
- Applying POS and dependency tools  
- Running classical ML models  
- Extracting structured insight from news content  
- Producing clear analytic visuals  

## Notes  
This midterm system forms the foundation of NewsBot 2.0 in the Final Project.  
You can find the upgraded final version in the folder ITAI2373-NewsBot-Final.
