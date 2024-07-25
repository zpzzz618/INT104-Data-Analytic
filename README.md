# INT104-Data-Analytic
This is the Coursework of the INT104 Artificial Intelligence module.
## Background
The goal of this project is to evaluate the physical condition of patients by designing a questionnaire with 15 questions and to determine the appropriate anesthesia method based on the scores of each question. A spreadsheet with scores from over 5000 patients is provided, with the results labeled as '0', '1', and a few as '2'. Students are required to design a classifier to categorize patients into the corresponding results based on the scores for each question. And done by three sub-tasks as follow:
* Task 1: Dimensionality reduction
* Task 2: Build Classifiers (Supervised Learning)
* Task 3: Unsupervised Patients Classification
## Method
This part will introduce the a machine learning (ML) approach based on Python's Scikit-Learn for patients classification to complete the three tasks
### Data Observation and Pre-preparing
#### Data Analysis
First, overview the first five lines of the raw data (csv file) to have a brief understanding. Then I find  the first column is the index number of the patient, the second to the sixteenth column is the answer to the fifteen questions, that is the fifteen features, and the seventeenth column is the result (which can be defined as label for supervised learning).

<img src="https://github.com/user-attachments/assets/f8a99fff-37f4-40da-9a04-0b8e120e060f" width=500px>
