# Resume Analyzer

A Python-based Resume Analyzer that extracts key sections, matches skills, and calculates an overall score based on the candidate's experience and skills. This tool uses fuzzy string matching to identify skills and compares them to a predefined list of desired skills. It also evaluates the years of experience mentioned in the resume.

## Features

- **Extract Key Sections**: Extracts key sections such as `Education` from resumes in PDF and DOCX formats.
- **Skill Matching**: Matches skills in the resume with a predefined list of desired skills using fuzzy matching.
- **Experience Extraction**: Extracts and calculates the total years of experience from the resume.
- **Score Calculation**: Calculates a resume score based on the number of matched skills and years of experience.
- **Skills Match Percentage**: Displays the percentage of desired skills found in the resume.
- **JSON Export**: Saves the analysis result to a JSON file for further review or processing.

## Predefined Desired Skills

The tool compares the skills in the resume with the following desired skills:

- Python
- Data Analysis
- Machine Learning
- Tableau
- PowerBI
- SQL
- Excel
- Communication
- Statistics
- Java
- C++
- AWS
- Cloud Computing
- Deep Learning
- Big Data
- Kubernetes
- Docker
- Hadoop
- Spark

## Requirements

- Python 3.x
- Required libraries:
  - `docx2txt`
  - `pdfminer.six`
  - `scikit-learn`
  - `nltk`
  - `fuzzywuzzy`
  
You can install the required libraries using `pip`:

```bash
pip install docx2txt pdfminer.six scikit-learn nltk fuzzywuzzy
