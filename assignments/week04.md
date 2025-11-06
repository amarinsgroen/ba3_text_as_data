# Week 4 Deliverable: Sentiment Analysis of Textbook Sentences

**Course:** Topical Reading: Digital Humanities (BA3 Korean Studies)  
**Instructor:** Steven Denney 
**Due:** Thursday, November 14, 2025 by 17:00

---

## 🎯 Objective
Reproduce the in-class **sentiment analysis workflow** in Orange Data Mining (ODM) using a keyword **other than 일본 (Japan)** and present clear, concise results.

---

## 🧩 Tasks

### 1. Choose a Keyword
Pick one word or phrase relevant to Korean history (for example: 미국, 근대화, 독립, 민족, 여성, 평화).  
Write 3–5 sentences explaining **why you chose this word** — it can be intuitive, tied to your interests, or motivated by something from the readings or a quick TF/DF/TF-IDF check.

### 2. Filter and Explore
Filter the corpus to **sentences containing your keyword**.  
Create **one simple exploratory visualization** (Word Cloud, Bar Plot, or Heat Map) to understand how your word appears in context.

### 3. Sentiment Analysis
- Setup and run the **Sentiment Analysis** workflow from the class demonstration.
- Remember to... 
	- **Filter out zeros** (`sentiment ≠ 0`).  
	- **Normalize** sentiment values to the interval **[–1, 1]** (Preprocess → Normalize).  
	- Create **at least** one data visual (e.g., Box or Violin plot) showing the sentiment distribution across periods.

### 4. Connect Scores to Actual Sentences & Exploration
Provide **examples of the sentences** behind your sentiment scores:
- Include a few (5-7) sentences** (mix of high, low, and moderate normalized sentiment, if you can).  
- Briefly explain **how you located these sentences** (for instance, via the Corpus Viewer, Data Table, or by saving selections).  Include the **period** and **normalized sentiment score** for each, if possible (it's just good context).  
- This is meant to be the *challenging* part — just do your best to associate results with real text. Don't worry about it being perfect!
- Feel free but not obliged to do additional analysis on documents and words to supplement your analysis.

### 5. Short Write-Up
Write up everything in a **brief report** (a few hundred words total will suffice) that includes:
- Why you chose your keyword  
- What you found about its tone or representation  
- Any visualizations you created
- Any quick notes on normalization, zero filtering, or retrieving example sentences

---

## 📦 Deliverables

Submit **two files only**:

- `week04_report.pdf` — your short write-up with plots and example sentences  
- `week04.ows` — your Orange Data Mining workflow

---

## Advice: Keep It Reasonable
One keyword. One exploratory visualization. One sentiment visualization.  
A short explanation and a handful of example sentences — that’s all that’s required.

---

## 💬 Optional R-Programming Track

Students who have been completing the **optional R-programming exercises** may choose to do this assignment entirely in **R** rather than in **Orange Data Mining**.  
The same analytical logic applies: select a keyword, perform exploratory analysis, compute sentiment, normalize, visualize, and briefly interpret.  
If you’re still gaining confidence in R, feel free to keep your workflow simple — the goal is to show understanding, not to produce complex code.  
Those not following the R track should continue using **Orange Data Mining**.  

For those completing the R version:  
- Your deliverables will be a **PDF report** and an **R script file (`.R`)**.  
- You may use **generative AI tools** (e.g., ChatGPT, Claude) for *guided assistance*, but you must be **transparent** about how you used them.  
- Please **save and submit** a downloaded copy of your gen AI chat history, so I can see what kind of help you received.  
- You are expected to write the R code yourself to the extent possible, using AI only for guidance, clarification, or debugging support.

---