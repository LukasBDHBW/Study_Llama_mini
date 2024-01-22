<p align="center">
  <img src="./Logo.png" alt="Dale Logo" width="200"/>
</p>

# Comparative Analysis of Retrained Llama 2 and Mini LLM Models

## Overview
This project focuses on the retraining and comparison of the Llama 2 model and a mini version of a Large Language Model (LLM) using data science educational data. Our goal is to analyze the effectiveness of these models in processing and understanding data science-related content.

## How to Run
For preprocessing and evaluation, an OpenAI API key is required, which should be written into a `config.ini` file in the following format:

```
[openai]
api_key = "API-Key"
```

1. **Preprocessing**: Install the requirements from `requirements.txt` using conda and install Tesseract OCR. `pytesseract` requires the Tesseract-OCR engine, which must be installed separately. The installation process varies depending on the operating system:

   - **Windows**:
     - Download the Tesseract installer from GitHub and execute it.
     - Note the installation path as you will need to specify it later in your Python script.

   - **Linux**:
     - Use the package manager of your distribution, for example on Ubuntu/Debian: `sudo apt-get install tesseract-ocr`

   - **macOS**:
     - Install it using Homebrew: `brew install tesseract`

2. **Running Notebooks**: The remaining notebooks can be executed on Kaggle, as we have added you as a collaborator there.


