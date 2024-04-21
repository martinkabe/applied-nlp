# Applied NLP Course

This repository contains the code and materials for the Applied NLP course.

## Course Description

This course is designed to provide a comprehensive introduction to natural language processing (NLP). The course will cover how to apply NLP to extract insights from text data and how to build predictive models using text data. The course will cover the following topics:

- Introduction to NLP

- Apply Pre-Trained Models

- Model Fine-Tuning

- Vector Databases

- Retrieval-Augmented-Generation

- OpenAI

-Open Source LLMs

- Prompt Engineering

- Data Augmentation

# Create a virtual environment

python -m venv .venv

or

virtualenv -p /usr/bin/python3 venv

# source virtual environment on linux

source .venv/bin/activate

# source virtual environment on Windows machine

source .venv/Scripts/activate

# for deactivating virtual environment simply use

deactivate

# Install fastapi and uvicorn

pip install fastapi "uvicorn[standard]"

# or if requirements.txt already provided

python -m pip install -r requirements.txt
