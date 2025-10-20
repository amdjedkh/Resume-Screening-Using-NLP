# ResuMe

## Overview

**ResuMe** is an intelligent resume screening system developed during the **Eleevo Internship (NLP Track)**.  
It leverages **Artificial Intelligence (AI)** and **Natural Language Processing (NLP)** to automatically analyze resumes, extract important information, and match them with job descriptions.  
The project aims to simplify recruitment and provide fast, fair, and accurate candidate evaluations.

## Key Features

- **AI Resume Parsing**: Automatically extracts key details (skills, education, experience) using NLP.
- **Smart Matching**: Uses cosine similarity to compare resumes with job descriptions.
- **Processing Pipeline**:
  - Text preprocessing
  - Entity extraction (NER)
  - Semantic similarity scoring
- **Interactive Interface**: React-based frontend for uploading resumes and viewing results.
- **Fast Backend**: Powered by FastAPI for high-performance processing.

## Technologies Used

- **Frontend**: React
- **Backend**: FastAPI
- **NLP Tools**: spaCy, Sentence Transformers
- **Machine Learning**: TF-IDF, Cosine Similarity, Named Entity Recognition (NER)
- **Languages**: Python, JavaScript

## Project Highlights

- Extracts and processes over 2,000 unique skills.
- Generates ranked compatibility scores for resumes.
- Achieved high accuracy and semantic understanding.
- Developed as part of the **Eleevo Internship Program**.

## Installation

### Prerequisites

- **Python 3.8+**
- **Node.js (with Yarn)**

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd ResuMatch
```

### Step 2: Frontend Setup

1. Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

2. Install dependencies:

    ```bash
    yarn install
    ```

3. Start the development server:

    ```bash
    yarn run dev
    ```

### Step 3: Backend Server Setup

1. Navigate to the `server` directory:

    ```bash
    cd server
    ```

2. Create a virtual environment:

    ```bash
    python3 -m venv env
    ```

3. Activate the virtual environment:

    - On Windows:

      ```bash
      .\env\Scripts\activate
      ```

    - On macOS/Linux:

      ```bash
      source env/bin/activate
      ```

4. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Run the FastAPI server:

    ```bash
    uvicorn app:app --reload
    ```

## Usage

1. Open the **Frontend**:
   - Navigate to `http://localhost:3000` in your browser (assuming the frontend is running).

2. Upload Resumes:
   - Use the provided UI to upload one or more resumes.

3. Specify Job Description:
   - Input or upload the desired job description for matching.

4. View Results:
   - The system will process the resumes and job description, returning a ranked list of resumes based on their compatibility scores.


</details>

## Acknowledgments

This project was developed as part of the Eleevo Internship (NLP Track), focusing on practical AI applications in recruitment automation.


