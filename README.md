# Zatoo Summari – AI Text Processing App

**DEMO** https://zatoo-summari-6gygegltp8fjunflkaoiyq.streamlit.app/

## About the Project

**Zatoo Summari** is an AI-powered web application built using Streamlit and Hugging Face Transformers. It provides multiple Natural Language Processing (NLP) tools through a simple, user-friendly interface.

Users can summarize long paragraphs, translate English text into French, analyze sentiment, and find answers from a given paragraph.

## Features

* **Text Summarization:** Generates a short summary of lengthy text.
* **Translation:** Translates English text into French.
* **Sentiment Analysis:** Identifies whether text expresses positive or negative sentiment.
* **Question Answering:** Finds answers to questions based on the provided context.
* **Interactive Interface:** Simple and easy-to-use Streamlit web application.
* **Pre-trained AI Models:** Uses Hugging Face Transformers models for NLP tasks.
* **Online Deployment:** Can be deployed using Streamlit Community Cloud.

## Technologies Used

* Python
* Streamlit
* Hugging Face Transformers
* PyTorch
* SentencePiece

## AI Models Used

| Feature                       | Model                                                        |
| ----------------------------- | ------------------------------------------------------------ |
| Text Summarization            | `google/flan-t5-base`                                        |
| English-to-French Translation | `Helsinki-NLP/opus-mt-en-fr`                                 |
| Sentiment Analysis            | `distilbert/distilbert-base-uncased-finetuned-sst-2-english` |
| Question Answering            | `distilbert/distilbert-base-cased-distilled-squad`           |

## Project Structure

```text
zatoo-summari/
|
|-- app.py
|-- requirements.txt
|-- README.md
```

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/madhuu2302/zatoo-summari.git
```

### Step 2: Navigate to the Project Folder

```bash
cd zatoo-summari
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
streamlit run app.py
```

## Online Deployment

This application can be deployed using Streamlit Community Cloud.

1. Upload the project files to GitHub.
2. Open Streamlit Community Cloud.
3. Connect your GitHub repository.
4. Select `app.py` as the main file.
5. Click **Deploy** to publish the application.

## Requirements

The project uses the following Python packages:

```text
streamlit
transformers==4.57.1
torch
sentencepiece
```

An internet connection is required to download the pre-trained models when they are first loaded.

## Project Objective

The main objective of this project is to demonstrate how pre-trained Natural Language Processing models can be integrated into a Streamlit application to perform different text-processing tasks through a single interface.

## Future Enhancements

* Support for additional languages.
* More advanced summarization options.
* File upload for text documents.
* Improved user interface.
* Support for additional NLP tasks.

## Developer

**Developed by:** Madhumitha

## Conclusion

Zatoo Summari demonstrates the practical use of Artificial Intelligence, Natural Language Processing, Hugging Face Transformers, and Streamlit to build an interactive text-processing application.

---

If you find this project useful, consider giving the repository a star.
