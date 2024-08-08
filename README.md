Resume Parser
-------------------
This Python script extracts key information from resumes in PDF format. It processes the resume to extract details such as name, email, phone number, LinkedIn profile, GitHub profile, GPA/percentage, skills, and education qualifications, displaying the results in a tabular format.

Features
---------------------
Extract Text: Extracts text from PDF resumes.
Contact Information: Extracts email address, phone number, LinkedIn profile, and GitHub profile.
Academic Information: Extracts GPA/percentage and educational qualifications with status (e.g., pursuing or completed).
Skills Extraction: Extracts and lists unique skills mentioned in the resume.
Tabular Display: Displays extracted information in a tabular format using Pandas DataFrame.

Requirements
---------------------
Python 3.7 or higher
spacy
pdfminer.six
pandas
