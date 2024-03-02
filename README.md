## Resume Revealer

**Project Overview:**

This project implements a system for automating resume processing, aiming to increase efficiency and reduce manual effort for companies. It leverages multiple machine learning models to extract and classify information from uploaded resumes.

**Key functionalities:**

* **Resume Parsing:** Parses uploaded resumes and extracts relevant details (name, contact information, etc.).
* **Section Classification:** Classifies the parsed text into sections like education, experience, and skills.
* **Occupation Prediction:** Predicts the most likely occupation for the candidate using a fine-tuned BERT model trained on job description and title data.
* **Skill Extraction:** Extracts relevant skills, using a pre-trained token classification model.

**Project Structure:**

* **resume parser.ipynb:** Handles resume upload and initial parsing.
* **section classifier.ipynb:** Classifies parsed text into different sections.
* **occupation classifier.ipynb:**
    * Fine-tunes a BERT model for occupation classification on ONET data.
    * Summarizes parsed text and uses the model to predict the occupation.
* **skill extractor.ipynb:** Extracts skills from classified sections using a pre-trained model.
* **final presentation.ppt:** A PowerPoint presentation explaining the project, its approach, and results.  

**Getting Started:**

1. **Prerequisites:**
    * Python 3
    * Necessary libraries
        * transformers
        * datasets
        * pandas
        * scikit-learn

2. **Run the project:**
    * Clone the repository.
    * Run scripts individually
    * Review the project information in `final presentation.ppt`


**Further Development:**

* Integrate the functionalities into a web application for user-friendly interaction.
* Explore advanced techniques for named entity recognition and skill extraction.
* Enhance the system by providing visualisations for lot of resumes provided.
