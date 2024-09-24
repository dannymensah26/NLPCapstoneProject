## Topic Modelling Using BBC News Articles Deployed on Streamlit App
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

## Phase 1: Exploratory Data Analysis (EDA) and LDA Model

In the initial phase, the project commences by delving into the Amazon Polarity dataset sourced from Hugging Face. The dataset undergoes a meticulous process of exploratory data analysis (EDA) to discern the distribution of sentiment, as well as to gather insights into word and sentence lengths.

To facilitate sentiment analysis, a Long Short-Term Memory (LSTM) model is employed, enriched by the integration of GloVe word embeddings. Two variants of the LSTM model are meticulously evaluated - one with 10 epochs, and another with a more robust 100-epoch training cycle. Learning rate scheduling through polynomial decay, coupled with the adam optimizer, is employed to refine the model. Further enhancements include the integration of early stopping, model checkpoints, and tensorboard callbacks. The models are rigorously assessed on the test data and further validated by predicting sentiments in custom reviews.
Exploratory Data Analysis (EDA) and Preprocessing

