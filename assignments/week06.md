# Week 6 Deliverable: Topic Modeling & LDA

**Course:** Topical Reading: Digital Humanities (BA3 Korean Studies)  
**Due:** Thursday, November 28, 2025 by 17:00

---

## 🎯 Objective
Build a simple LDA model in Orange, explore topics with LDAvis, and interpret what topic modeling reveals about your corpus.

---

## 🧩 Tasks

### 1. Build an LDA Model in Orange
- Load `nikh__sentences.csv` (in `/data/nikh`)  
- Preprocess (tokenize, stopwords; noun-only script optional)  
- Add **Topic Modeling**  
- Choose a reasonable number of topics (4-6 should be fine)  
- Connect to **Data Table** to view topic–document probabilities  

**Export:** `week06_flow.png`

---

### 2. Explore Topics with LDAvis
- Connect Topic Modeling → LDAvis  
- Select **two topics**  
- Use the **λ slider (0.2–0.35)**  
- Take screenshots of the word relevance view  

**Export:** `topic_X_ldavis.png`

---

### 3. Interpret Topic–Document Mixtures
- Pick **three documents** in the Data Table  
- For each:
  - Which topic has highest probability?  
  - Any topics with probability 0? 
  - Briefly interpret what this suggests  

Write 2–4 sentences per document in your `README.md` for this week.

---

### 4. Short Reflection
In your `README.md` (5–7 sentences):
- What themes did your topics represent?  
- How did λ change interpretation?  
- One strength and one limitation of LDA.
- What might you do _next_ in your analysis pipeline?

---

### 5. Submit Your .ows File
Upload your Orange workflow: `week06.ows`

---

## 📦 Deliverables (folder structure)

/week06/
├── week06_flow.png
├── topic_1_ldavis.png
├── topic_2_ldavis.png
├── week06.ows
└── README.md


