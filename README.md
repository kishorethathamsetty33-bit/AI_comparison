# AI Document Comparison Assistant

An AI-powered web application that compares two PDF documents using Python, Streamlit, pypdf and the Gemini API.

## Project Overview

The AI Document Comparison Assistant helps users compare two versions of text-based PDF documents.

The application:

- Uploads two PDF documents
- Validates the uploaded files
- Extracts text using pypdf
- Shows extracted text statistics and preview
- Generates a separate summary for each document
- Identifies similarities
- Identifies meaningful differences
- Compares important details
- Generates an overall conclusion
- Displays processing limitations
- Generates a downloadable DOCX comparison report

## Technology Stack

- Python
- Streamlit
- pypdf
- Google Gemini API
- google-genai
- Pydantic
- python-dotenv
- python-docx
- Git
- GitHub

## Project Structure

```

## Configure the Gemini API key

1. Create an API key in Google AI Studio.
2. Copy `.env.example` to a file named `.env` in the project root.
3. Replace `your_gemini_api_key_here` with your API key, without adding quotes.
4. Start or restart the app from the project directory:

   ```powershell
   streamlit run app.py
   ```

The application reads the key from the `GEMINI_API_KEY` environment variable.
Keep `.env` private; it is excluded from Git.text
ai-document-comparison-assistant/
│
├── app.py
├── document_reader.py
├── comparison.py
├── report_generator.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
│
└── sample_documents/
