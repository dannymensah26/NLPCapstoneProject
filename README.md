## Sentiment Analysis - Amazon Polarity
## Overview

This sentiment analysis project focuses on understanding and classifying the sentiment expressed in product reviews. The project encompasses three distinct phases, each contributing to the comprehensive sentiment analysis pipeline. Leveraging a subset of the amazon_polarity dataset, the project employs two powerful models: an LSTM model with GloVe embeddings and a fine-tuned DistilBERT. The LSTM model achieved an accuracy of 80.40%, while the DistilBERT model outperformed with an impressive 90.75% accuracy. Additionally, a user-friendly Streamlit app was developed to provide real-time sentiment analysis capabilities, ensuring seamless deployment for end-users.

Phase 1: Exploratory Data Analysis (EDA) and LSTM Model

Phase 2: Fine-tuning DistilBERT

Phase 3: Streamlit App Deployment

GitHub|Link

Notebooks|Link

Demo|Link

## Demo App

Check out the deployed Streamlit app for live predictions here.

## Libraries Used
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- scipy
- wordcloud
- textblob
- TQDM
- pyLDAvis
- gensim
- streamlit
- nltk==3.5

## Git Clone and Run the App

1. Clone the Repository

       git clone https://github.com/dannymensah26/NLPCapstoneProject.git

2. Install Dependencies

       pip install -r requirements.txt

3. Run the App

       streamlit run app.py


