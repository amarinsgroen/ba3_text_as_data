# Topical Reading: Digital Humanities  
Course: BA3 Korean Studies, Leiden University  
Instructor: Dr. Steven Denney  
Time & Place: Fridays, 11:15–13:00, Huizinga 0.09  
Duration: 6 seminars starting October 10 and ending November 21

---

## Expanded Course Description
This is the DH strand of the BA3 course **Contemporary Korea and Digital Humanities**. This course is meant to introduce students to digital humanities (DH) methods, focusing on text-as-data approaches. Using Orange Data Mining and pre-prepared Korean corpora, students will learn how to clean, analyze, and interpret textual data.  

The DH strand complements the topical reading seminars by equipping students with methodological skills to support their undergraduate research and to introduce them to the DH side of research in the Humanities and Social Sciences. There are no programming requirements whatsoever in this course, although students will have the opportunity to explore ways to acquire such skills.

Students will learn how to prepare, analyze, and interpret text using **Orange Data Mining**. The aim is not technical mastery, but to understand how computational methods can support thesis research in the KoreaStudies (BA) program at Leiden University.

---

## Tutorials  
Each week lists required **Orange Data Mining Tutorials**.  
- These tutorials are **required viewing before class**.  
- They are short (≈5–10 minutes each) and introduce the widgets you will use hands-on.  
- Watching them in advance will free up class time and have you better prepared for applying methods to Korean corpora.

👉 You can download the Orange Data Mining application **[HERE](https://orangedatamining.com/)**  
👉 Tutorials (to watch before class) are available here: [Orange Data Mining Tutorials (YouTube Playlist)](https://www.youtube.com/playlist?list=PLmNPvQr9Tf-ZSDLwOzxpvY-HrE0yv-8Fy)

---
## Assignments

In addition to attending weekly sessions, you are required to complete **weekly assignments (“deliverables”)**. These tasks reinforce the skills introduced in tutorials and class exercises. Assignments can be found in the folder marked with the same name ([Assignments](https://github.com/scdenney/ba3_text_as_data/tree/main/assignments)).

### Format
- Each deliverable consists of:  
  1. One or more screenshots of your Orange workflow/output  
  2. A short written reflection (≈1 paragraph)

### Submission
- Commit your deliverables to your GitHub repository in the appropriate weekly folder (e.g., `week01/`, `week02/`, etc.)  
- **Deadline:** 17:00 on the Monday following class  
- **Grading:**  
  - `2` = fully complete and accurate  
  - `1` = attempted but not fully complete/accurate  
  - `0` = incomplete, late, or not attempted  
- **Note:** You do *not* need to upload assignments to Brightspace. The instructor will review your GitHub repo and record grades.

### Examples
- *Week 1:* Set up your GitHub repo + README reflection on DH and thesis research  
- *Week 2:* Screenshot and reflection on text preprocessing (raw vs. cleaned text)  
- Later weeks: continue the same format — apply tutorials, document results, and reflect on significance

👉 **Weekly deliverables, together with attendance, make up 30% of your DH strand grade** (see Assessment section).

---

## GitHub Repository Requirement  
See the ["how-to" guide](repo_how-to.md) (located in the syllabus folder) on how to get started with GitHub and repo management.

You are required to maintain a **private GitHub repository** for this course:  

1. Create a new private repo named: `DH-TopicalReading-<Surname>`.  
2. Add the instructor (**username: scdenney**) as a collaborator.  
3. Keep the repo private, unless you explicitly choose to share it.  
4. Organize the repo with the following structure:

📂 Student Repository Structure
<pre>
DH-TopicalReading-<Surname>/
  ├── assignments/    # where you commit your assignments
│   ├── week01/
│   │   ├── week01-deliverable.md
│   │   └── screenshots/
│   ├── week02/
│   │   └── ...
│   ├── week06/
│   └── final-project/
└── README.md          # use the README to introduce yourself and what your repo will do for you
</pre>

5. Each week’s deliverable (markdown file + screenshots) must be committed to the correct subfolder.  
6. At the start of the course, submit the **URL of your repo** to the instructor at [this Google Sheet](https://docs.google.com/spreadsheets/d/1iVdwLTfmVkMn2cQGXPxCC4YIxADawSKAWltZIxD5WMs/edit?usp=sharing) (click to open).

This organization mirrors best practices for **research data management** and is part of the course’s learning objectives.  

---

## Corpus Overview

The primary dataset for this course is the 국사편찬위원회 (Kuksap’yŏnch’an Wiwŏnhoe; National Institute of Korean History, NIKH) history textbook corpus. This collection brings together Korean history textbooks produced under successive national curricula, spanning from the late 조선 (Chosŏn; Joseon) and 대한제국 (Taehan Cheguk; Korean Empire) through the 일제강점기 (Ilche Kangjŏmgi; Japanese colonial period), liberation, and the postwar 교육과정 (kyoyuk kwajŏng; national curricula) up to the present. These textbooks, published and authorized by the state, offer an authoritative view of how the Korean nation, state, and people have been represented by state-sanctioned education across different political eras.

You may peruse an online-navigable version of the history textbooks through the National Institute of Korean History’s official website: [contents.history.go.kr](https://contents.history.go.kr/front/ta/main.do)  

Because textbooks are central to the formation of collective memory and national identity, this corpus is especially well suited for exploring questions of modern Korean identity: how ideas of 민족 (minjok; nation/people), 국민 (kungmin; citizens), 시민 (simin; civic belonging), and 통일 (t’ongil; unification) have been framed, contested, and transmitted to generations of (South) Korean students. In this way, the corpus links directly to broader themes in modern political sociology in Korea, which you are also examining in the topical reading strand of this course. 

For **supplementary purposes**, additional pre-prepared corpora are available:  
- **개벽 (Kaebyŏk, 1920–1935):** An interwar magazine reflecting cultural, intellectual, and political debates in colonial Korea. *Kaebyŏk* has been used extensively in scholarship on cultural nationalism and modern identity, including Michael Robinson’s *Cultural Nationalism in Colonial Korea, 1920–1925* (1988), Andre Schmid’s *Korea Between Empires, 1895–1919* (2002), and Henry Em’s “Minjok as a Modern and Democratic Construct: Sin Ch’aeho’s Historiography” (1999).  
- **경제연구 (Kyŏngje Yŏngu, 1987–2017):** A North Korean economics journal, useful for examining how policy and ideology interact in the DPRK. Read more about this at [38 North](https://www.38north.org/2025/05/in-memoriam-kyongje-yongu/).  

👉 Other corpora will be introduced during the course to support student exploration. For the final project, students will be required to use one of the pre-prepared corpora, except the NIKH practice corpora, or to have approved the use of one of their own. We will discuss how to design a mini text-as-data project throughout the course and especially in Week 6.

---

## Weekly Outline (subject to change)

### Week 1 (Oct. 10): Introduction to DH, GitHub & Data Management
- **Lecture:** What is DH? Why text-as-data matters for Korean Studies. FAIR data principles.  
- **Hands-On:** GitHub setup, orientation to Orange workflows and widgets.  
- **Tutorials:** *Welcome to Orange, Data Workflows, Widgets & Channels*.  
- **Deliverable:** Create GitHub repo + README reflection.  

---

### Week 2 (Oct. 17): Text Preprocessing with Aron v/d Pol
- **Lecture:** Tokenization, stopwords, normalization. Korean-specific preprocessing challenges.  
- **Hands-On:** Import corpora, apply preprocessing, compare raw vs. cleaned.  
- **Tutorials:** *Text Preprocessing, Importing Text Documents*.  
- **Deliverable:** Preprocessing workflow screenshot + reflection.  

---

### Week 3 (Oct. 24): Descriptive Patterns
- **Lecture:** Frequency, keywords, word clouds. From descriptive to interpretive claims.  
- **Hands-On:** Group analysis of corpora, frequency/word cloud outputs, keyword contrasts, clustering/projection.  
- **Tutorials:** *Text Clustering, Multivariate Projection (Freeviz)*.  
- **Deliverable:** Word cloud + clustering screenshot + reflection.  

---

### Week 4 (Nov. 7): Classification & Prediction
- **Lecture:** Supervised methods, labels, evaluation, and applications in thesis research.  
- **Hands-On:** Apply sentiment classification, evaluate accuracy, discuss limits.  
- **Tutorials:** *Text Classification, Making Predictions, Model Evaluation*.  
- **Deliverable:** Classification screenshot + reflection.  

---

### Week 5 (Nov. 14): Clustering & Similarity
- **Lecture:** Unsupervised methods; clustering documents. Strengths and pitfalls.  
- **Hands-On:** Hierarchical and k-means clustering, silhouette evaluation, interpret clusters.  
- **Tutorials:** *Hierarchical Clustering, k-Means, Silhouette*.  
- **Deliverable:** Clustering screenshot + ≈1-page reflection.  

---

### Week 6 (Nov. 21): Topic Modeling & Wrap-Up
- **Lecture:** Introduction to topic modeling (LDA). Comparing clusters vs. topics. Designing a DH project.  
- **Hands-On:** Run topic modeling on a corpus, interpret top words per topic, compare with clustering.  
- **Tutorials:** *Topic Modeling widget demo*.  
- **Deliverable:** Topic model output + reflection.  

---

### Final Project (Nov. 28)

The final project will take the form of an **in-person, four-hour “hackathon”** held in the DH Lab. Working in small groups, students will complete a text-as-data analysis project that draws directly on the skills developed in this six-week strand of the course.

Each group will:

* Select from a pre-prepared corpus (or set of corpora). It will be possible to use your own.
* Formulate a research question.
* Design and carry out a workflow in Orange Data Mining.
* Generate and interpret findings.
* Write up results and a brief reflection on the process.
* Submit it to Brightspace.

This is a **timed, in-class assignment** (not a take-home project). Further details will be provided in advance.


---

## Assessment
The DH strand of the course is worth 25% of the full course grade. That 25% is broken down as follows:
- Weekly Deliverables & Attendance (6 × 5% = 30%)  
- Final Project (70%)

---

## Attendance
Full attendance is expected. Missing any sessions will put you behind. If you cannot attend all sessions, speak with the instructor in advance.
