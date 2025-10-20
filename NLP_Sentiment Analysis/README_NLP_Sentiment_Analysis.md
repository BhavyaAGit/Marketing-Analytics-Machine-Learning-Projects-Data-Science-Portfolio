# NLP – Sentiment Analysis  
### RetailPulse: Data-Driven Sentiment & Topic Analysis of Customer Reviews  

---

### Project Overview  
This project applies **Natural Language Processing (NLP)** and **Machine Learning** to analyze customer review text, detect sentiment, and extract key discussion topics.  
It demonstrates how businesses can leverage unstructured feedback to improve marketing strategy, brand positioning, and customer satisfaction.

---

### Business Objective  
To uncover actionable insights from customer reviews by:  
- Measuring **positive vs. negative sentiment** across channels.  
- Identifying **top reasons for dissatisfaction or delight** (price, service, product quality, delivery).  
- Quantifying **brand perception trends** and providing input for campaign strategy.  

---

### Methodology  
1. **Data Cleaning & Preparation**  
   - Text tokenization, stopword removal, lemmatization.  
2. **Feature Engineering**  
   - TF-IDF vectorization and n-gram analysis.  
3. **Modeling**  
   - Logistic Regression & Linear SVM for binary sentiment.  
   - **LDA Topic Modeling** for discovering hidden discussion themes.  
4. **Transformer Polarity**  
   - Hugging Face model `distilbert-base-uncased-finetuned-sst-2-english` for contextual sentiment scoring.  
5. **Aspect-Level Sentiment**  
   - Price, Quality, Delivery, Support, Usability.  
6. **Evaluation**  
   - Accuracy, F1, ROC-AUC, confusion matrix, feature importance.  

---

### Files in This Folder  
| File | Description |
|------|--------------|
| `RetailPulse_NLP_Driven_Sentiment_and_Topic_Analysis_of_Customer_Reviews.ipynb` | Main notebook containing full workflow |
| `reviews_nlp_synth.csv` | Synthetic dataset (~25 k reviews) used for analysis |
| *(optional)* `outputs/` | Generated CSVs for dashboarding (sentiment scores, aspect roll-ups) |

---

###  How to Run  
```bash
# Install dependencies
pip install -r ../../requirements.txt

# Launch Jupyter Notebook
jupyter notebook RetailPulse_NLP_Driven_Sentiment_and_Topic_Analysis_of_Customer_Reviews.ipynb
```

---

### Key Insights  
- ~70 % of reviews classified as **Positive**.  
- Major negative topics: *delivery time*, *pricing*, *support response*.  
- Transformer polarity and classical ML models show > 90 % alignment in sentiment direction.  

---

### Next Steps  
- Integrate streaming review data for near real-time analysis.  
- Build Power BI / Streamlit dashboard.  
- Fine-tune domain-specific BERT model for improved accuracy.

---

© 2025 Bhavya Priya Akula | Marketing Analytics & Machine Learning Portfolio
