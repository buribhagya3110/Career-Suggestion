🚀 Overview

The AI Job Recommender System is a machine-learning and NLP-based project designed to automatically analyze resumes and suggest ideal job profiles. The system extracts key skills, identifies the candidate’s domain, and matches it with a curated job dataset to generate accurate recommendations.

This project helps users understand their strengths, improves their resume relevance, and assists recruiters in quick job-role classification.


🚀 Features
FastAPI backend with automatic API docs Resume Upload Support (.pdf, .docx)
NLP Resume Parsing (text extraction + cleaning)
Skill Extraction (technical + soft skills)
Job Recommendation Engine based on skill matching
Simple Web UI for viewing results
MCP-ready for integration with AI agents or automation tools


🛠️ Tech Stack
Frontend
•	HTML, CSS
•	JavaScript

Backend
•	Python
•	FastAPI
•	Uvicorn

Machine Learning / NLP
•	spaCy / NLTK
•	Scikit-learn

Others
•	File handling
•	Regex-based cleaning
•	Job role dataset

🧩 How It Works
1.	User uploads a resume file
2.	Resume Parser extracts:
	•	skills
	•	experience
	•	education
	•	keywords
3.	ML/NLP model predicts domain
4.	Job Recommender matches with job dataset
5.	System displays top job recommendations


📌 Future Enhancements
•	Add support for LinkedIn profile parsing
•	Integrate real-time job APIs (Indeed, Naukri, LinkedIn Jobs)
•	Improve domain prediction using deep learning models
•	Add multi-language resume support


