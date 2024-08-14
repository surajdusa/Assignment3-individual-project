# Assignment3-individual-project
# Infosys Data LLM

## Project Overview
This project demonstrates the process of fine-tuning a pre-trained BERT model (BERT-base-uncased) to classify financial data extracted from Infosys's annual reports. The goal is to predict binary outcomes based on financial descriptions, utilizing the Hugging Face Transformers library and PyTorch in Google Colab.

## Installation

### Prerequisites
- Python 3.7+
- pip

### Libraries
Install the required libraries using pip:

```bash
pip install -r requirements.txt
Usage
To use this project, follow these steps:
1.Clone this repository.
2.Ensure you have the necessary Python packages installed:
bash
pip install -r requirements.txt
3.Open the Infosys Data LLM.ipynb notebook in Google Colab or Jupyter Notebook.
4.Follow the instructions in the notebook to run the model training and evaluation.
## **Model Training**
The model is trained on the financial data provided in the Excel files, which include descriptions and financial figures from Infosys's financial statements over several years. The model predicts whether the financial amounts exceed a certain threshold.

## **Files**
Infosys Data LLM.ipynb: Jupyter Notebook containing all the code and documentation.
requirements.txt: File containing all required Python libraries.
model/: Directory where the trained model and tokenizer are saved.
## **License**
This project is licensed under the MIT License - see the LICENSE.md file for details.

