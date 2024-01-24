<p align="center">
  <img src="./Logo.png" alt="Dale Logo" width="200"/>
</p>

# Comparative Analysis of Llama 7B base and finetuned model & efficient distilling of Llama 1.4B

## Overview
This project focuses on the retraining and comparison of the Llama 2 model and a mini version of a Large Language Model (LLM) using data science educational data. Our goal is to analyze the effectiveness of these models in processing and understanding data science-related content.

## How to Run
For preprocessing and evaluation, an OpenAI API key is required, which should be written into a `config.ini` file in the following format:

```
[openai]
api_key = "API-Key"
```

1. **Preprocessing**: Install the requirements from `requirements.txt` using:

```
pip with pip install -r requirements.txt
```

 and install Tesseract OCR. `pytesseract` requires the Tesseract-OCR engine, which must be installed separately. The installation process varies depending on the operating system:

   - **Windows**:
     - Download the Tesseract installer from GitHub and execute it.[Link](https://ub-mannheim.github.io/Tesseract_Dokumentation/Tesseract_Doku_Windows.html)

   - **Linux**:
     - Use the package manager of your distribution, for example on Ubuntu/Debian: `sudo apt-get install tesseract-ocr`

   - **macOS**:
     - Install it using Homebrew: `brew install tesseract`


2. **Running Notebooks**: The remaining notebooks can be executed on Kaggle, as we have added you as a collaborator there.

    - **Finetuning Notebook**: https://www.kaggle.com/code/wmarcus/fork-of-finetuning-problems-in-core-notebook/notebook?scriptVersionId=160287283

    (original notebook, but access management setting issues in kaggle for some reason, so there is no access possible currently for new users) https://www.kaggle.com/code/wmarcus/llama-kaggle-tuning?scriptVersionId=160285615


    - **Finetuning Eval Notebook**: https://www.kaggle.com/code/wmarcus/fork-of-llama-vs-edullama-eval/notebook


    - **Layer extraction + finetuning notebook for distilled model (first 2 steps of graphic)**: https://www.kaggle.com/code/wmarcus/distil-new-trial/notebook?scriptVersionId=160285293


    - **Distillation (core output distil process) notebook**: https://www.kaggle.com/code/wmarcus/qa-output-distillation?scriptVersionId=160292332


Graphic Distillation:
<p align="center">
  <img src="./Llama Bild.PNG" alt="Dale Logo" width="600"/>
</p>
