# Final Project Groups & Assignment Overview

## 📋 Group Assignments

| Group | Members |
|-------|---------|
| **1** | Bhowmick, Moro |
| **2** | Kwakernaak, Braamhaar, van de Meerakker |
| **3** | van Dixhoorn, Boas, Verdegaal |
| **4** | Sem Hoes, Geurtsen, Ridderhof |
| **5** | Kools, Soares Silves Ferreira, Groen |
| **6** | Haan, van Zevenbergen, van der Vorm |
| **7** | Stückmann, de Jong, van de Weijer |

---

# 🧪 Final Project: In-Class Text-as-Data Hackathon  
**Date & Time:** December 5, 10:00am - 2:00pm
**Duration:** 4 hours (in-person, in the DH Lab)

This is a **timed, in-person assignment** completed in groups. You will apply the skills learned in the six-week Digital Humanities: Text-as-Data strand to complete a full text-as-data analysis using Orange Data Mining (ODM).

The emphasis is on **the process**, not necessarily the findings. A careful, well-reasoned workflow is more important than a “big discovery".

---

## 📚 Available Corpora  
You will choose from one of **five (5)** pre-prepared corpora.  

For each corpus, you will receive:

- A short description  
- Key metadata (source, time period, document count, etc.)  
- Notes on any preprocessing considerations  

Corpora and overviews will be released *48 hours* prior the hackathon. You are encouraged to plan ahead with your group, especially regarding the reserch question.
As noted, you may also use **your own corpus**, but they be must approved prior to the 24 hour pre-release window.

---

# 🧭 What Your Group Must Do

## 1. Select a corpus  
Pick one corpus.

## 2. Formulate a research question  
Your question must be specific and answerable. Avoid broad or unfocused questions.

---

## 3. Build a workflow in Orange  
Your workflow must be **clear**, **logical**, and **replicable**.

We are looking for the following components (and anything else that is reasonable given your question):

- Bag-of-Words (counts or TF-IDF) 
- Clustering  
- Topic modeling  
- Sentiment analysis  
- Keyword extraction or embeddings  
- Any additional widgets that support your reasoning 
- Data visuals appropriate to express findings derived from the above

Include appropriate preprocessing (tokenization, stopwords, etc.).

### **Qualitative Verification (Required)**  
Your workflow must include **some qualitative verification**, meaning:

- You read portions of selected documents  
- Or, for sentence-level corpora, you read the **entire document**  
- Selections must follow a **logic** (e.g., extreme cluster examples, high-weight keywords, outliers, topic exemplars)  
- When possible, use ODM tools such as **Concordance**, **Corpus Viewer**, or **Select Rows** to support close readings

Qualitative reading is essential to confirm or challenge your computationally-driven results.

---

## 4. Generate and interpret results  
Explain what the outputs show and link them back to your question. Use data visuals or tables where appropriate, and be sure to appropriately label figures and tables.

Again: the quality of the **process** matters more than producing a dramatic or “correct” finding.

---

## 5. Write a short PDF report  
A concise, structured manuscript that includes the following elements:

- Research question 
- Research motivation (see more below)
- Corpus used  
- Workflow overview (i.e., what you did, how, and why)
- Key results  
- Interpretation  
- Limitations  
- Reflection on the process  

**Re: Research motivation:** You are expected to "motivate" or justify your research quesiton as something appropriate for the study of Korea. Why is it interesting, and why should should we be interested in answering it. You may bring in outside academic and/or popular sources to support this, but this is _not_ a literature review. Keep it (relatively) brief.

**Target Report Length:** approximately 1,800–2,500 words total, including figures/tables (counted as ~250 words each). Focus on clarity, reasoning, and verification. A longer report does not mean a better report/grade; the goal is a well-structured analysis that demonstrates understanding of the tools and the logic behind the workflow. There is no hard floor or ceiling on word count, although your ability to express yourself and explain adeqeuately your workflow in less than 1,500 words, including figures and table, will be a challenge.

---

# 📦 Final Deliverables 

One person submits to the instructor via email (s.c.denney@hum.leidenuniv.nl), with all other group members CC'd. You must use your official Leiden University email account.

Your group will submit **all** of the following as a .zip file:

1. **PDF Report (required)**  
2. **`.osw` Orange workflow file (required)**  
3. **Appendix (optional)**  
4. **`.R` file (if you used R for any part of the analysis)**

---

# ✔️ Assessment Criteria (Scores 0–10)

Your final project grade is based on **four weighted criteria**, each graded **0–10**.  
The **final grade** is the **weighted average** (rounded to one decimal) of the four criterion below.

| Criterion | Weight | Description |
|----------|--------|-------------|
| **Research Question** | **15%** | Clear, specific, feasible, and appropriately aligned with the corpus. |
| **Workflow Quality** | **30%** | Logical, well-structured workflow; correct widget use; `.osw` runs cleanly. |
| **Interpretation of Results** | **40%** | Accuracy, clarity, and depth in explaining and verifying outputs. |
| **Report Quality (PDF)** | **15%** | Overall structure, clarity, writing, and professional presentation. |

An assessment report will be returned via email as a response to the submission.

---

## What the Scores Mean (0–10)

**0–3** — *Insufficient*  
- Major problems in logic, execution, or understanding.  
- Workflow may not run; interpretation incorrect or missing.

**4–5** — *Weak / Nearly sufficient*  
- Partial understanding; inconsistent reasoning; unclear writing.  
- Workflow mostly runs but with errors, gaps, or unjustified choices.

**6** — *Sufficient*  
- Basic competence demonstrated.  
- Workflow usable; interpretations mostly correct but shallow or limited.  
- Report understandable but not especially clear.

**7** — *More than sufficient*  
- Good, coherent analysis with reasonable justification.  
- Interpretation correct; report clearly written.

**8** — *Good / Very good*  
- Strong reasoning and workflow; meaningful qualitative verification.  
- Well-organized report; clear interpretation with insight.

**9** — *Excellent*  
- High-level understanding; precise reasoning; thoughtful verification.  
- Professional report; workflow is clean and replicable.

**10** — *Outstanding*  
- Exceptional work across all dimensions.  
- Creative but appropriate analytical decisions; deeply insightful interpretation.  
- Almost no improvements possible within the assignment constraints.


---

This final project evaluates your ability to design, execute, verify, and explain a text-as-data analysis under realistic time constraints. The focus is on thoughtful reasoning, not producing the “right” answer.
