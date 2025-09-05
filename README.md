# Prompt Engineering for Data Cleaning Tasks

## Overview
This project showcases how prompt engineering powers data cleaning tasks using Google Gemini. The pipeline transforms unstructured inputs like text, images, and PDFs into clean, structured JSON outputs, then converts those into usable formats like CSV.

## Features
- **Support Log Parsing**: Turn free-text customer support logs into structured JSON.
- **Urgency Detection**: Automatically tag text by urgency levels.
- **Invoice Extraction**: Parse invoice images into structured JSON.
- **Resume Parsing**: Extract fields like education, skills, and projects from PDF resumes.
- **Output Management**: Store structured results in CSV for downstream analysis.

## Tech Stack
- **Python**
- **Google Generative AI (Gemini)**
- **dotenv** for secure API key handling
- **pandas** for data processing and output handling

## Prerequisites
- Python 3.x
- Valid Google Gemini API access (API key in `.env`)

## Setup & Usage

```bash
git clone https://github.com/SidJanawade/Prompt-Engineering-for-data-cleaning-tasks.git
cd Prompt-Engineering-for-data-cleaning-tasks
pip install -r requirements.txt   # or install dependencies manually
