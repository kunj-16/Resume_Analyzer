#LLM Based Resume Analyzer, ATS Score and JD Match Analyzer


## Objective
Develop an end-to-end Applicant Tracking System (ATS) using Google Gemini Pro Vision API. This project will enable you to analyze resumes, compare them with job descriptions, and receive actionable suggestions for enhancing your resume to better match job requirements.
## Input Text 
Job Description and CV uploaded
## Output / Response
CV Score , Things that can be improved in CV, Skills Improvement Suggestions 

## Features

- **JD PErcentage Calculation**: Automatically evaluates the CV against job descriptions.
- **Improvement Suggestions**: Provides specific areas for improvement in the CV.
- **Skill Improvement Suggestions**: Identifies and suggests skills that can be added or improved in the CV.

## Requirements

- Python 
- Streamlit
- google.generativeai
- Google Gemini Pro Vision API Key
- streamlit
- PyPDF2


## Installation

1. **Clone the Repository**

    ```bash
    https://github.com/kunj-16/Resume_Analyzer/
    ```

2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up API Key**

    Create a Google Gemini Pro Vision API key and set it as an environment variable.

    ```bash
    export GEMINI_PRO_API_KEY='your_api_key'
    ```

## Usage

1. **Run the Application**

    ```bash
    streamlit run app.py
    ```

2. **Upload Job Description and CV/Resume**

    - Open your browser and go to the URL displayed by Streamlit.
    - Upload your Job Description and CV in the provided interface.

3. **Get Results**

    - The application will analyze the CV against the Job Description.
    - You will receive a PErcentage match, suggestions for improvement, and skill improvement suggestions.

## Project Structure

- **app.py**: Main application file that runs the Streamlit frontend.
- **requirements.txt**: List of dependencies required for the project.


