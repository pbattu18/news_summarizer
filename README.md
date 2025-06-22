# Real-Time News Scrapper and Summarizer

This project is a real-time news summarization system that fetches the most recent headlines on any given topic and condenses them into a short, easy-to-read summary. The goal is to provide readers with a quick and informative glance at what has happened in the last 24-72 hours surrounding any topic, individual, or organization.
___

## Project Overview
This project was designed to:

- Automatically scrape news articles based on a given query (e.g., company name, public figure, or event).

- Extract relevant titles and descriptions from these articles.

- Summarize this content into a short paragraph (~150-200 words).

The system is intended to replace manual Googling and browsing through several news links by giving a concise, factual digest.

___

## Use Case & Mission

In today's fast-paced world, we rarely have time to sift through dozens of news headlines. 
The mission of this project was to solve that problem by:
- Offering real-time awareness of any topic.

- Highlighting key developments and collective media sentiment.

- Enabling more informed decision-making, faster.

Use cases include:

- Investors researching companies

- Students keeping up with news

- Social media creators prepping takes on breaking stories

___

## Technologies Used

- Python: Core scripting language

- NewsAPI: For fetching real-time news articles from major sources

- Transformers by HuggingFace: Pretrained summarization model (facebook/bart-large-cnn)

- BART (Large CNN variant): A state-of-the-art summarization model fine-tuned specifically for condensing news articles

- Kaggle Notebook Environment: All development and testing were done directly on Kaggle, ensuring ease of reproducibility and no local dependencies

___
##  Why This is Better Than Googling

| Method       | Drawbacks                                             | This Model Solves             |
|--------------|--------------------------------------------------------|-------------------------------|
| Google Search| Too many links, no summaries, unstructured timelines | Condenses key points in one go|
| Twitter      | Noisy, biased, or outdated takes                      | Fact-based, neutral summary   |
| Manual Reading| Time-consuming                                       | Fully automated + real-time   |

Instead of bouncing between 10+ tabs and articles, you get one snapshot that tells you exactly what's going on.

---

##  Summary Model Insights

- Used `facebook/bart-large-cnn` which is pre-trained on news corpora  
- Able to summarize ~3000 characters of text, and chunked for longer input  
- Results were found to be:
  - Factually correct  
  - Concise and readable  
  - Strong at identifying high-level themes  

---

## ✅ What Was Achieved

- ✔ A fully working summarizer app using NewsAPI and BART  
- ✔ Real-time headline fetching and condensing  
- ✔ Kaggle-hosted, single-notebook implementation (no API key exposure)  
- ✔ Open-source and extendable to multi-day or multi-source setups  

---

##  How to Use

1. Go to the notebook on Kaggle  
2. Enter a topic string (e.g., "Google", "Artificial Intelligence", "Ukraine")  
3. The app fetches articles from the last few days  
4. Summary is generated and displayed automatically  

---

##  Future Work

- Build a UI using Streamlit or Gradio  
- Add sentiment classification alongside the summary  
- Expand input to cover social media + Reddit + financial filings  
- Enable multi-day trend summarization (e.g., what changed over a week?)  

---

##  Acknowledgements

- HuggingFace for the pretrained summarization models  
- NewsAPI for simple and efficient access to current headlines  

---

##  Author
Project developed as a part of a learning path in NLP and AI-powered product design by [@pbattu18].










