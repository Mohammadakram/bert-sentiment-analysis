# bert-sentiment-analysis
Comparative study of BERT fine-tuning techniques on IMDB, Twitter, Instagram, and ChatGPT datasets.
# 🧠 BERT Sentiment Analysis: Comparative Study
### Natural Language Processing (NLP)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mohammadakram/bert-sentiment-analysis-dissertation)

## 📌 Project Overview
This project performs a comprehensive comparative analysis of **BERT (Bidirectional Encoder Representations from Transformers)** for sentiment classification. The study evaluates the impact of **hyperparameter tuning** (Optimizers, Learning Rates) and **text pre-processing** (Lemmatization, Stop-word removal) across four diverse datasets.

## 📂 Repository Structure
The project is organized by dataset. Click on a folder to view specific implementations:

| Folder | Description |
| :--- | :--- |
| **`01_IMDB_Sentiment_Analysis`** | 50k Movie Reviews. Baseline for BERT Base vs. BERT Large. |
| **`02_Instagram_App_Reviews`** | Analysis of app store reviews for Instagram. |
| **`03_Twitter_Sentiment140`** | Short-text sentiment analysis (1.6m tweets). |
| **`04_ChatGPT_Reviews_Analysis`** | Sentiment analysis on user reviews of ChatGPT. |

## 🛠 Tech Stack & Methodology
- **Model Architecture**: BERT Base (uncased), BERT Large.
- **Optimizers Compared**: AdamW vs. SGD (Stochastic Gradient Descent).
- **Preprocessing**: Comparisons of raw text vs. Lemmatization/Stop-word removal.
- **Libraries**: PyTorch, Hugging Face Transformers, Scikit-learn, Pandas.

## 📊 Key Findings
- **Optimizers**: AdamW consistently outperformed SGD in convergence speed and final accuracy across all datasets.
- **Preprocessing**: Aggressive preprocessing (stop-word removal) actually *reduced* BERT's accuracy in some contexts, as BERT leverages context from common words.
- **Learning Rates**: Lower learning rates (2e-5) proved more stable for fine-tuning than higher rates (5e-5).

## 🚀 How to View the Notebooks
**Note:** If GitHub fails to render the `.ipynb` files, please use [nbviewer](https://nbviewer.org/) or click the "Open in Colab" badge above.

1. Copy the URL of the notebook you want to view.
2. Paste it into [nbviewer.org](https://nbviewer.org/).

## 👤 Author
**Mohammad Akram**
*MSc Computing | Data Analytics & NLP Enthusiast*
[LinkedIn Profile][(https://www.linkedin.com/in/your-profile-link)](https://www.linkedin.com/in/akram-mohammad1/)
