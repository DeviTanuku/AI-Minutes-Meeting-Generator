
# 🧠 AI Meeting Minutes Generator

This project automatically generates concise, human-like meeting summaries and analyzes sentiment from raw transcripts using NLP techniques. Built using **Google Colab** and **Gradio**, it allows users to interact with the tool through a simple web interface.

---

## 🚀 Features

- 📄 **Summarization using TextRank and LSA models**  
- 💬 **Sentiment analysis** to classify tone as *positive*, *negative*, or *neutral*  
- 📊 **Evaluation with METEOR and ROUGE** metrics  
- 🌐 **Interactive UI via Gradio**

---

## 📁 Dataset

Used publicly available **Meeting Transcripts Dataset** from [Kaggle](https://www.kaggle.com/).  
(Data not included in repo due to size restrictions.)

---

## 🔄 Workflow

1. **Preprocessing & Text Cleaning**  
2. **Model Implementation**  
   - TextRank  
   - LSA (Latent Semantic Analysis)  
3. **Evaluation**  
   - METEOR Score  
   - ROUGE Score  
4. **Sentiment Analysis**  
5. **Gradio Interface for User Interaction**

---

## 📊 Evaluation Metrics

- **METEOR:** Based on Precision, Recall, and word order  
- **ROUGE:** Measures n-gram overlap between generated and reference summaries

---

## 🌐 Live Demo

Gradio App: Demo Video is added for reference.

---

## 🛠 Tools & Libraries

- Google Colab  
- Gradio  
- NLTK  
- Scikit-learn  
- NumPy  
- Matplotlib  
- Figma *(for prototyping UI flow)*

---

## 📌 How to Run

1. Open the Colab notebook from this repo  
2. Run all cells to process the transcript and launch Gradio interface  
3. Upload transcript → Get Summary + Sentiment Output instantly

