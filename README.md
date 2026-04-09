# 🏥 Sentiment Analysis of Public Health Complaints using Deep Learning (RoBERTa)

## 📌 Project Overview
This project was developed during my Data Science Internship at the **Public Relations Division, Central Java Provincial Health Office (Dinkes Jateng)**. The goal was to transform unstructured public complaint data (from Instagram, WhatsApp, and Web Portals) into actionable quantitative insights using Natural Language Processing (NLP).

## 🎯 Business Problem
Manually reading and classifying hundreds of public complaints is time-consuming and subjective. The management needed an automated, objective system to categorize public sentiment (Positive, Negative, Neutral) to quickly identify service bottlenecks and prioritize public health issues.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Deep Learning Framework:** Hugging Face Transformers (RoBERTa-base), PyTorch
* **Data Processing:** Pandas, NumPy, NLTK, Sastrawi
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colaboratory

## 🚀 Methodology
1. **Data Collection:** Processed 181 real-world public complaint records (Jan - Jun 2025).
2. **Text Pre-processing:** Conducted Case Folding, URL/Mention/Hashtag Removal, Slang Normalization (custom dictionary), and Stopword Removal tailored for informal Indonesian.
3. **Modeling:** Implemented Transfer Learning using the pre-trained `indonesian-roberta-base-sentiment-classifier`.
4. **Post-processing:** Applied Rule-Based Correction to ensure informational queries were strictly labeled as 'Neutral'.

## 📊 Key Results
* Successfully automated the sentiment classification process.
* **Sentiment Distribution:** Neutral (82.32%), Negative (9.39%), Positive (8.29%).
* The negative sentiment data was isolated and used by the Public Relations team to evaluate specific healthcare facility complaints.

<img width="863" height="580" alt="gambar" src="https://github.com/user-attachments/assets/5f243ea3-827a-4308-b408-ffa8e4a762f0" />

## 💡 What I Learned
Through this project, I gained hands-on experience in building an end-to-end NLP pipeline, fine-tuning pre-processing techniques for informal languages, and translating Deep Learning outputs into business value for a government institution.
