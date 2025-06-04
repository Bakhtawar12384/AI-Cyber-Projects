# AI-Cyber-Projects

#  AI-Powered Cybersecurity & Multimedia Intelligence Projects

This repository showcases two AI-driven projects .

---

## 1. Vulnerability Assessment with AI (VARE)

**Objective:**  
To automate vulnerability severity classification and provide intelligent remediation suggestions using AI.

###  Features
- **Data Sources:**
  - [NVD CVE feeds](https://nvd.nist.gov/)
  
- **AI Components:**
  - **Severity Classifier:** Categorizes vulnerabilities as Low, Medium, High, or Critical.
  - **Remediation Engine:** Suggests fixes using a fine-tuned T5 or DistilBART model or retrieval via SBERT.
- **NLP & ML Stack:**
  - SBERT/BERT for embeddings
  - Logistic Regression, Random Forest, or Transformers
- **Evaluation Metrics:** Accuracy, F1, BLEU, ROUGE, Semantic Similarity
- **Enhancements (Optional):**
  - Chat interface for remediation Q&A
  - Threat feed integration (e.g., MITRE ATT&CK, Shodan)
  - Business-context-based risk scoring

---

##  2. AI Multimedia System: Movie Genre & Audio Summary Generator, FILMCEPTION

**Objective:**  
To create an interactive system that predicts movie genres and converts summaries into audio across multiple languages.

###  Key Functionalities
- **Genre Prediction:**
  - Trained on [CMU Movie Summary Dataset](https://www.kaggle.com/datasets/msafi04/movies-genre-dataset-cmu-movie-summary)
  - Multi-label classification using models like Logistic Regression or BERT
- **Audio Summary Conversion:**
  - Translate summaries into **Arabic**, **Urdu**, and **Korean**
  - Convert translated text into speech using tools like gTTS or pyttsx3
- **NLP Preprocessing:**
  - Cleaning, tokenization, lemmatization, and metadata extraction
- **Interactive Menu-Driven Interface:**
  - Input a summary → Choose audio conversion or genre prediction → Output result accordingly

---

##  Tech Stack

- **Languages:** Python
- **Libraries:** Scikit-learn, Hugging Face Transformers, gTTS, Pyttsx3, Pandas, NLTK, TTS APIs
- **ML/NLP Tools:** BERT, SBERT, T5, DistilBART, TF-IDF, Word2Vec

---

##  How to Run

1. Clone this repo  
   `git clone https://https://github.com/Bakhtawar12384/AI-Cyber-Projects

2. Set up environment (recommend using `venv` or `conda`)

3. Run the corresponding scripts from:
   - `vare/` → For vulnerability assessment
   - `movie-ai/` → For genre prediction and audio summary
