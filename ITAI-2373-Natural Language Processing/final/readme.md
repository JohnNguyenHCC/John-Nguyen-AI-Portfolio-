# NewsBot Intelligence System 2.0  
ITAI 2373 Final Project  
Author: John Nguyen  

## Overview  
NewsBot 2.0 is an advanced NLP system that processes news articles and extracts meaningful insight.  
It expands the midterm NewsBot into a full production style platform with classification topic modeling sentiment analysis summarization semantic search multilingual features and a simple conversation tool.  
The system runs fully on Google Colab with open libraries and no external API keys.

## Key Features  
- Improved Linear SVM classification  
- LDA topic modeling  
- Article and topic level sentiment scoring  
- Extractive and abstractive summaries  
- Semantic search using transformer embeddings  
- English to French translation  
- Natural language query interface  

## Files Included  
```
ITAI2373-NewsBot-Final/
│
├── NewsBot2_Final.ipynb
├── README.md
├── bbc_news_sample_final.csv
│
├── FP_TechnicalDoc_JohnNguyen_Solo_ITAI2373.pdf
├── FP_ExecutiveSummary_JohnNguyen_Solo_ITAI2373.pdf
└── FP_ReflectiveJournal_JohnNguyen_Solo_ITAI2373.pdf
```

## How to Run  
1. Open the notebook in Google Colab  
2. Upload the BBC News Train.csv dataset when prompted  
3. Run all cells from top to bottom  
4. The system will output categories topics sentiment summaries and search results  

## System Workflow  
1. Preprocess and clean raw text  
2. Generate TF IDF features and embeddings  
3. Classify articles  
4. Build topics  
5. Score sentiment  
6. Create summaries  
7. Search content semantically  
8. Translate and compare tone  
9. Answer natural language questions  

## Skills Demonstrated  
- Advanced NLP pipeline design  
- Classification and topic modeling  
- Sentiment and tonal analysis  
- Semantic search and embedding models  
- Summarization methods  
- Multilingual text handling  
- System integration and documentation  

## Notes  
This folder represents the final upgraded version of the NewsBot system.  
The midterm version can be found in the sibling directory named ITAI2373-NewsBot-Midterm.


