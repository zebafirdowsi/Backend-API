# Student Question Classifier API 

A **FastAPI** backend API to classify student questions into one of three predefined topics: **Math**, **Science**, or **English**.

## Features

- **POST /classify-question**: Classifies a student’s question into a topic and returns the confidence score.
- **GET /questions**: Returns a list of all previously classified questions with topics and confidence scores.
- **Logging**: Saves incoming questions and results to a local `questions.json` file.

## Requirements

- Python 3.7 or higher
- FastAPI
- Uvicorn (for serving the app)
- use the `/docs` endpoint to test the API.


To install the dependencies:

```bash
pip install fastapi uvicorn
For Google Colab setup:
!pip install fastapi uvicorn pyngrok nest_asyncio
