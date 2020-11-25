# Fake Job Recruitment Posting Detection

## Libraries used
1. numpy
2. pandas
3. matplotlib
4. wordcloud
5. sikit learn
6. nltk
7. spacy

## Project file details
### 1. data-mining-project.ipynb
A ipython notebook made on kaggle and configured with properties to work on kaggle's directory structure. It contains the code of data cleaning for the project.

### 2. fake_job_postings.csv
The dataset used for this project lies in this file. The dataset has been prepared by The University of the Aegan. The dataset contains following columns:
1. job_id: Unique Job ID
2. title: The title of the job ad entry
3. location: Geographical location of the job ad
4. department: Corporate department (e.g. sales)
5. salary_range: Indicative salary range (e.g. $50,000-60,000)
6. company_profile: A brief company description
7. description: The details description of the job ad
8. requirements: Enlisted requirements for the job opening
9. benefits: Enlisted offered benefits by the employer
10. telecommuting: True for telecommuting positions
11. has_company_logo: True if company logo is present
12. has_questions: True if screening questions are present
13. employment_type: Full-type, Part-time, Contract, etc
14. required_experience: Executive, Entry level, Intern, etc
15. required_education: Doctorate, Master’s Degree, Bachelor, etc
16. industry: Automotive, IT, Health care, Real estate, etc
17. function: Consulting, Engineering, Research, Sales etc
18. fraudulent: target - Classification attribute

### 3. clean_data.csv
This file contains preprocessed data for further use in the models.

### 4. data-mining-project2.inpynb
A ipython notebook made on kaggle and configured with the properties to work on kaggle's directory. It contains code of final data cleaning and dividing in to test and train set and different models for prediction. it also compares the final predicted output's ROC-AUC score graphically.
