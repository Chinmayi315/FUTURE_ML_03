# Resume / Candidate Screening System

This project builds an intelligent Resume Screening System that automatically evaluates and ranks resumes based on a given job description using Natural Language Processing (NLP) and Machine Learning techniques.

---

## 🚀 Problem Statement

Recruiters often receive hundreds of resumes for a single job role. Manually reviewing them is:

- Time-consuming  
- Inconsistent  
- Error-prone  

This system automates resume screening by comparing resumes with job requirements and ranking candidates accordingly.

---

## 🎯 Objectives

- Perform text preprocessing on resumes  
- Extract key skills using NLP  
- Match resumes with job description  
- Rank candidates based on relevance  
- Identify missing skills  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Dataset

This project uses a Resume Dataset containing:

- Resume text data  
- Job categories  

Dataset Source: Kaggle Resume Dataset  

(Note: Dataset is not uploaded due to size constraints)

---

## ⚙️ Methodology

1. Text Cleaning (lowercase, remove special characters, stopwords)  
2. Skill Extraction from resumes  
3. Job Description processing  
4. TF-IDF Vectorization  
5. Cosine Similarity calculation  
6. Skill matching  
7. Final scoring & ranking  

---

## 📊 Scoring Formula

Final Score = (0.6 × Similarity Score) + (0.4 × Skill Score)

- Similarity Score → Text relevance  
- Skill Score → Matching skills  

---

## 📈 Output

The system provides:

- Ranked candidates  
- Extracted skills  
- Missing skills  
- Final score  

---

## ✅ Conclusion

This project demonstrates how NLP and Machine Learning can automate resume screening and improve hiring efficiency.

---

## 🔮 Future Improvements

- Use BERT / Transformers  
- Improve skill extraction using NLP models  
- Build web-based interface  
- Include experience & education scoring  

---

## 📜 License

This project is licensed under the MIT License.
