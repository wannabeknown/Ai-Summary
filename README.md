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

## Setup Instructions

1. **Get Hugging Face API Key**: Sign up on [Hugging Face](https://huggingface.co/) to get an API key.
2. **Import Postman Collection**: Import the provided Postman collection (`TextSummarizerCollection.json`) into Postman.
3. **Configure Environment Variable**: Set the `user_input` environment variable with the text to summarize.

## Usage

1. **Set Authorization**: In Postman, set up Bearer Token authorization with your Hugging Face API key.
2. **Enter Text to Summarize**: Set the `user_input` environment variable in Postman.
3. **Send Request**: Send the POST request, and view the summarized output in the response body.

## Sample Request & Response

### Request Body
```json
{
  "inputs": "Johannes Gutenberg introduced the printing revolution in Europe..."
}

![image](https://github.com/user-attachments/assets/3a47c44f-d817-4501-abe4-164e018ccf8a)

