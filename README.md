# Aspect-Based Sentiment Analysis for Turkish E-Commerce Reviews Using BERTurk

This repository contains the official implementation and resources for the research project: **"Aspect-Based Sentiment Analysis for Turkish E-Commerce Reviews Using BERTurk"**. 

This work focuses on a fine-grained sentiment analysis approach, identifying specific aspects (e.g., Price, Delivery, Quality) within Turkish customer reviews and classifying their associated sentiments using transformer-based architectures.

## 📌 Project Overview
While traditional sentiment analysis provides a general polarity for a text, this project implements an **Aspect-Based Sentiment Analysis (ABSA)** framework. It allows for a more nuanced understanding of customer feedback by breaking down reviews into specific categories relevant to the e-commerce domain.

The system utilizes **BERTurk**, a state-of-the-art BERT model pre-trained specifically for the Turkish language, fine-tuned on a comprehensive dataset of 54,416 reviews.

## 🚀 Key Features
- **Large-Scale Turkish Dataset:** Utilized 54,416 reviews across 10 different categories.
- **Fine-Tuned BERTurk Model:** Optimized for the morphological and semantic complexities of Turkish.
- **Unsupervised Aspect Detection:** Leveraged **Sentence-BERT (SBERT)** and **K-Means Clustering** for initial aspect discovery.
- **Multi-Task Learning:** Simultaneous identification of aspects and sentiment polarities.

## 🛠️ Tech Stack
- **Language:** Python
- **Core Model:** BERTurk (dbmdz)
- **Frameworks:** PyTorch, Transformers (Hugging Face)
- **Tools:** SBERT, Scikit-learn, Pandas, NLTK

## 📖 Research Publication
For detailed methodology, experimental results, and performance metrics, please refer to the full paper:

> **Hozan Baydu, Serkan Eren, Ahmet Furkan Faideci.** *"Aspect-Based Sentiment Analysis for Turkish E-Commerce Reviews Using BERTurk"*. 
> **Full Paper:** [ResearchGate Link](https://www.researchgate.net/publication/401020330_Aspect-Based_Sentiment_Analysis_for_Turkish_E-Commerce_Reviews_Using_BERTurk)

## 📊 Methodology Highlights
1. **Data Pre-processing:** Extensive cleaning and tokenization of Turkish e-commerce data.
2. **Aspect Discovery:** Grouping reviews into latent themes using embedding-based clustering.
3. **Model Training:** Fine-tuning BERTurk with a "Gold Standard" annotated subset for high precision.

## 👨‍💻 Author
**AI Engineer** M.Sc. in Artificial Intelligence, Gebze Technical University  
B.Sc. in Electrical Engineering, Yıldız Technical University
