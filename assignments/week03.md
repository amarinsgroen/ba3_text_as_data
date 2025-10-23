# Week 3 Deliverable: Clustering Documents and Understanding Text Weights

**Course:** Topical Reading: Digital Humanities (BA3 Korean Studies)  
**Date:** October 23  
**Instructors:** Steven Denney & Aron van der Pol

**Due:** Thursday, October 30, 2025 by 17:00 (longer than usual!)

---

## 🎯 Objective

Learn how text preprocessing and weighting schemes (raw counts vs. TF-IDF) affect document clustering and keyword extraction in Orange Data Mining (ODM). Also, explore the value of document clustering.

---

## 🧩 Tasks

### 1. **Read and Reflect on Text Preprocessing** (Python file)
   - Open and read through the annotated `.py` file on text preprocessing. It's in the `/data` folder. Note: there are files with and without annotations. You can use either, but it's cleaner to use the one without in ODM.
   - Try running the custom Python script; it keeps only nouns (common and proper nouns), FYI.
   - If yes, continue using it. If no, that's fine; revert to your previous preprocessing pipeline.
   - Let us know in your `README.md` for this week if it worked, any questions you have, etc. 

### 2. **Compare Word Counts vs. TF-IDF**
   
   **a) Export two visualizations:**
   - Create a **Word Cloud or Bar Chart** using **raw word counts** (unweighted)
   - Create a **Word Cloud or Bar Chart** using **TF-IDF weights**
   - For both: limit the number of words displayed to a reasonable amount (e.g., 50-100 words)
   - Save both visualizations, upload them.
   
   **b) Analysis:**
   - What **changes** between raw counts and TF-IDF?
   - What **stays the same**?
   - What does this tell you about how TF-IDF works?
   - Write your observations in your `README.md` (3-5 sentences is fine)

### 3. **Hierarchical Clustering and Cluster Analysis**
   - Follow the instructor's pipeline to generate **hierarchical clusters** from the nikh corpus
     - (Hint: The `.ows` file is available in the `/presentations` folder if you need help)
   - Select at least 2 different clusters from the dendrogram
   - For each cluster, generate either a **Word Cloud** or **Bar Plot** showing the top words
     - Remember to limit the number of words displayed
     - Label each export clearly (e.g., "cluster_1_wordcloud.png", "cluster_2_wordcloud.png")
   
   **Write a short report:**
   - Use any word processor you prefer
   - Explain:
     - What you did (your clustering approach)
     - Why you did it (what you were trying to discover)
     - What you found (what do the clusters represent? What themes emerged?)
   - Don't worry about length; just write enough to clearly explain your process and findings
   - Export as **PDF** and upload to your assignments folder

### 5. **Provide your .ows file**
   - Show your flow! Upload it, please.
---

## 📦 Deliverables

Place the following files in your GitHub repo folder for week03 assignment:

**Folder structure:**
```
/week03/
│
├── raw_counts_visualization.png
├── tfidf_visualization.png
├── clustering_report.pdf
├── week03.ows
└── README.md
```

**README.md should include:**\
- Thoughts about running a custom python script.
- Your comparison of raw counts vs. TF-IDF

---

## 💡 Optional (R Track)

For students in the **R Programming extension**, complete:

**DataCamp – Introduction to Text Analysis in R**
- Module 2: *Visualizing Text*
- Module 3: *Sentiment Analysis*

R track assignments are due **before the next class**.
