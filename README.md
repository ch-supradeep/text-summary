Text Summarization using Natural Language Processing (NLP)
Overview
This project implements a text summarization system using Natural Language Processing (NLP) techniques. The goal is to automatically generate concise and coherent summaries of input text, enabling users to quickly grasp the main points of lengthy documents.

Features
Extractive Summarization: Utilizes algorithms to identify and extract key sentences from the input text to form the summary.
Abstractive Summarization : Incorporates advanced NLP models to generate summaries that may not be present in the original text.
Pre-trained Models: Allows users to choose from pre-trained models for summarization or train their own models based on specific requirements.
Web Interface : Provides a user-friendly web interface for easy interaction with the summarization system.
Installation
Clone the repository:

git clone https://github.com/ch-supradeep/text-summarization.git
cd text-summarization
Install dependencies:
pip install -r requirements.txt
Download pre-trained models
python download_models.py
python summarize.py --input_path input.txt --output_path summary.txt
--input_path: Path to the input text file.
--output_path: Path to save the generated summary.
Web Interface (Optional)
python app.py
