# AI-Powered Candidate Matching Engine (NLP)
## Bridging HR Expertise with Data Science

### 📌 Project Overview
As an HR professional transitioning into Business Analytics, I developed this tool to solve a common recruitment bottleneck: **Manual Resume Screening**. 

This Python-based engine automates the comparison between Job Descriptions and Candidate Profiles. Unlike basic keyword searches, it uses Natural Language Processing (NLP) principles to normalize text and calculate an "Intersection Score" based on Set Theory.

### 🛠️ Technical Stack
- **Language:** Python
- **Libraries:** Pandas (Data Manipulation), Matplotlib (Visualization)
- **Concepts:** Tokenization, Text Normalization, Lambda Functions, Set Theory (Intersection).

### ⚙️ How it Works
1. **Text Pre-processing:** Converts all strings to lowercase and removes punctuation to ensure "Python," matches "python".
2. **Tokenization:** Breaks down long skill strings into individual "Tokens".
3. **Scoring Logic:** Uses a `Set Intersection` algorithm to calculate the percentage of job requirements present in the candidate's profile.
4. **Visualization:** Generates a "Talent Pipeline" bar chart to rank candidates by match percentage.

### 📈 Business Impact
- **Efficiency:** Reduces the time spent on initial resume screening by automating keyword matching.
- **Data-Driven Hiring:** Provides a standardized "Match Score" to remove human bias during the first round of selection.
- **Scalability:** The logic can be scaled to thousands of resumes using the optimized `.apply()` and `lambda` functions.

---
**Contact Information:**
- **Name:** Sahil Kumar
- **Role:** MSc Business Analytics Graduate | HR Professional
- **Location:** London, UK
