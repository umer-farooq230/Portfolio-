# My-Portfolio
These are the collection of my personal projects. This is a **meta-repo**, meaning each project lives in its own GitHub repository, but this README serves as the central hub.
 
---

### 1. Intrusion-Detection-for-MQTT-Networks 
**Description:**  
An end-to-end anomaly detection pipeline for MQTT-based IoT networks. Data is ingested from a SQL database, preprocessed, and exported to CSV. Multiple models were experimented with, and the best onewas deployed and monitored using MLflow.

**Tech Stack:**  
`Python`, `SQL`, `scikit-learn`, `MLFlow`, `Pandas`

**Problem:**  
IoT networks are vulnerable to cyberattacks, but raw traffic data is messy and hard to work with.

**Solution:**  
Built a workflow that converts and cleans data in SQL, experiments with supervised and unsupervised models, and monitors results with MLflow.

**🔗 Repo:** [Intrusion-Detection](https://github.com/umer-farooq230/Intrusion-Detection-for-MQTT-Networks)

---

### 2. Fine-Tuning LLaMA 3.1 with Unsloth for Text-to-SQL
**Description:**  
This project fine-tunes the unsloth/Meta-Llama-3.1-8B model using the GretelAI synthetic text-to-SQL dataset. Uses Low Rank Adaption technique to reduce the computational cost

**Tech Stack:**  
`Python`, `Transformers`, `Unsloth`, `LLaMA 3`, `Datasets`, `LoRA`, `Text-to-SQL`, `Colab`

**Problem:**  
Many Text-to-SQL solutions require large compute or training from scratch.

**Solution:**  
The goal is to help the model generate accurate SQL queries with explanations based on natural language prompts and database descriptions.

**🔗 Repo:** [llama3-text-to-sql-unsloth](https://github.com/umer-farooq230/NL2SQL-Fine-Tuning)

---

### 3. Hidden Markov Model Regime Detection System
**Description:**  
A state-based model that identifies short-term regime shifts in high-frequency OHLCV data using statistical features, PCA, and probabilistic state transitions. Currently refining the system for faster updates and more stable regime boundaries.
**Tech Stack:**  
`pandas`, `numpy`, `hmmlearn`, `PCA`, `Monte Carlo`

**Problem:**  
High-frequency data is noisy and non-stationary, making it difficult to understand when the market environment changes.

**Solution:**  
An HMM framework that models hidden states, compresses inputs with PCA, checks stability with LLN-based rolling estimates, and uses Monte Carlo sampling to test boundary robustness. This captures regime changes more reliably and in near–real-time.

**🔗 Repo:** This is still under production 

---

### 4. Sentiment Analysis (End-to-End Pipeline)
**Description:**  
Collects, cleans, analyzes, and visualizes user reviews from Google Play Store apps. Supports multi-class sentiment classification (e.g., Positive, Neutral, Negative).

**Tech Stack:**  
`Python`, `Pandas`, `Scikit-learn`, `XGBoost`, `Streamlit`, `matplotlib`, `seaborn`

**Problem:**  
App developers receive thousands of reviews but struggle to identify trends or UX issues.

**Solution:**  
An end-to-end pipeline that scrapes, analyzes, and visualizes sentiment trends across app categories.

**🔗 Repo:** [google-play-sentiment-pipeline](https://github.com/umer-farooq230/Sentiment_Analysis)

---


## 👋 Who Am I?

I'm Umer — I build intelligent and end to end systems. Currently pursuing AI/ML and forecasting applications, with a love for projects that are both clever and useful.

Let’s connect on:
- 🧠 [LinkedIn](https://www.linkedin.com/in/umer-farooq230/)
- 💌 [Email](umerfarooq230@gmail.com)
