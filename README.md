# Ai-Summary
A text summarization tool using Hugging Face's API and Postman


# Text Summarizer API

This project demonstrates a text summarization tool using Hugging Face’s NLP API, integrated with Postman for easy testing and interaction.

## Overview

This tool allows users to input lengthy text and receive a concise summary. The project uses the `google/pegasus-xsum` model from Hugging Face, making it useful for summarizing articles, research papers, and other lengthy content.

## Technologies Used

- Hugging Face Inference API
- Postman
- JSON, REST API

## Features

- **Text Summarization**: Summarizes input text into a brief, clear output.
- **User-Friendly Input**: Allows users to enter text via Postman’s environment variables.

## Text Summarizer API Collection

This repository includes a Postman collection for a text summarization tool using the Hugging Face Inference API.

### Importing the Collection

1. **Download** the `TextSummarizerCollection.json` file from this repository.
2. Open **Postman** and go to the **Collections** tab.
3. Click **Import** and select the downloaded JSON file.
4. Once imported, set up your environment variables and API key as needed.

### Example Usage

After importing, you can use this collection to test the text summarization API. Make sure to:
- **Set your Authorization** with the Hugging Face API key.
- **Configure the `user_input` environment variable** in Postman with the text to be summarized.

## Sample Request & Response

### Request Body
```json
{
  "inputs": "Johannes Gutenberg introduced the printing revolution in Europe..."
}
```
## Response 
![image](https://github.com/user-attachments/assets/3a47c44f-d817-4501-abe4-164e018ccf8a)
