# Project Name: ChatPdf
## Project Overview:
ChatPdf is a Streamlit-based application designed for interactive question-answering tasks on PDF documents using natural language processing and AI models.

## Libraries Used:
streamlit: For building the interactive web application.
langchain_community: For document loading and text splitting.
langchain_google_genai: For Google's generative AI embeddings and chat capabilities.
dotenv: For loading environment variables like API keys.
langchain: For various NLP chains and utilities.
google.generativeai: Google's Generative AI API.
## Features:
PDF Document Handling: Loads PDF documents using PyPDFLoader.
Text Splitting: Splits documents into manageable chunks using RecursiveCharacterTextSplitter.
Embeddings: Uses Google Generative AI Embeddings for text representation.
Question-Answering: Implements a question-answering system using a retrieval-augmented generation (RAG) approach.
User Interaction: Allows users to ask questions interactively via a web interface.
## Setup:
Ensure you have Python installed (preferably Python 3.7+).
Install required packages using pip install -r requirements.txt.
Set up environment variables for GOOGLE_API_KEY and GROQ_API_KEY in a .env file.
Run the application using streamlit run app.py.

## Deployment:
Hosted Link: ChatPdf[https://gangaguru-q-a-chatpdf.streamlit.app/]
Provide the link to your deployed Streamlit application where users can access it.
## Usage:
Access the application through the Streamlit interface in your browser.
Upload or specify the path to a PDF document.
Enter questions related to the content of the PDF.
Receive answers based on the document content and AI capabilities.
### Example .env File:
GOOGLE_API_KEY=your_google_api_key
GROQ_API_KEY=your_groq_api_key
### Notes:
Make sure to handle API keys securely and avoid sharing them publicly.
Customize the UI and functionalities as per your project requirements.
