
# Aisha Amirkyzy - Data Science & AI Portfolio

Hello! I am a senior undergraduate Data Science student at SDU University, Founder & Lead of the SDU Data Community (230+ members), and an applied ML researcher.

- **GitHub:** [github.com/aisha-collab](https://github.com/aisha-collab)
- **LinkedIn:** [linkedin.com/in/aisha-amirkizy](https://linkedin.com/in/aisha-amirkizy)
- **Email:** amirkyzyaisha@gmail.com

## Core Skills
* **Programming & Tech Stack:** Python (Pandas, NumPy, Scikit-learn, PyTorch), SQL, FastAPI, Docker, Git/GitHub.
* **Data Science & AI:** Machine Learning, Logistic Regression, Deep Learning (RNN/LSTM), NLP, Data Scraping.
* **Analytics & Visualization:** Streamlit, Google Looker Studio, Exploratory Data Analysis (EDA), Data Storytelling.
* **Project Delivery:** Stakeholder Communication, Requirements Gathering, Agile Task Prioritization.

---

## Featured Projects

### 1. Almaty Parking Monitor (`almaty-parking-monitor`)
* **Question:** How can we systematically track, monitor, and analyze urban parking availability and spatial distribution across Almaty?
* **Data:** 212 deduplicated parking locations dynamically scraped from the 2GIS API using spatial geo-grid analysis.
* **Method:** Developed an automated Python data scraper, processed geographic coordinates using spatial data handling, and integrated automated notification workflows (Twilio WhatsApp alerts).
* **Main Result:** Successfully deployed a working monitoring system that captures real-time spatial data updates and triggers automated alert pipelines.
* **What I Learned:** Mastered API data ingestion, working with geospatial data formats, and setting up automated notification triggers.
* **Code & Resources:** [View Project on GitHub](https://github.com/aisha-collab/almaty-parking-monitor)

---

### 2. Chicago Food Inspections - Predictive Risk Modeling (SDS 307 Core Project)
* **Question:** Can we accurately predict whether a food establishment will pass or fail a sanitary inspection based on historical violation records and facility features?
* **Data:** Official *Chicago Food Inspections* dataset from the Chicago Data Portal ($16,935$ cleaned observations; binary Pass/Fail target).
* **Method:** Built a binary logistic regression pipeline with L2 regularization using Scikit-learn, feature engineering (violation counts, critical flags), and stratified 70/30 train-test splitting with `StandardScaler`.
* **Main Result:** Achieved an overall test accuracy of **81.72%** at optimal $C=1$, identifying infraction counts as the primary driver reducing passing odds by nearly 79% per standard deviation.
* **What I Learned:** Understood how class imbalance impacts false positives in regulatory machine learning models and how L2 regularization stabilizes coefficients.
* **Code & Resources:** [View Project Code in Repository](./projects/chicago_inspections/)

---

### 3. Emotion Classification (NLP) - Deep Learning Model (`emotion-classifier-project`)
* **Question:** How can we accurately classify customer emotions and sentiment from text using recurrent neural network architectures?
* **Data:** Text-based customer sentiment dataset featuring tokenized sentences mapped to emotion classes.
* **Method:** Built an end-to-end Natural Language Processing (NLP) pipeline in **PyTorch** utilizing text tokenization, vectorization, and deep learning **LSTM/RNN** architectures.
* **Main Result:** Successfully trained and evaluated a recurrent neural network model capable of capturing sequential dependencies in text to classify emotional intent.
* **What I Learned:** Gained deep practical experience in tensor operations, handling text embeddings, and training recurrent neural networks (RNN/LSTM) in PyTorch for classification tasks.
* **Code & Resources:** [View Project on GitHub](https://github.com/aisha-collab/emotion-classifier-project)

---

## Professional Experience & Achievements
* **SDU Data Community (2024 - Present):** Founder & Lead. Built a 230+ member student community from scratch, onboarding 20 industry mentors.
* **SDU AI Lab (2025 - Present):** AI / ML Researcher. Owned full ML delivery pipelines and shipped REST APIs using FastAPI and Docker.
* **Freedom Course Scholar (2025 - 2026):** Sponsored by Freedom Holding Corp.; built analytics dashboards and presented at Freedom Demo Day 2026.
* **Hackathon Achievement:** 2nd Place at the Freedom Ecosystem Challenge Hackathon 2026.
