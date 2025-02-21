# PDF Report Summarizer

This repository contains a Python script that extracts and summarizes key financial insights from PDF reports using Google's Gemini API.

## Features
- Extracts text from PDFs using PyMuPDF (`fitz`)
- Cleans and preprocesses extracted text
- Summarizes key investor insights using Gemini AI
- Supports file upload in Google Colab

## Requirements
- Python 3
- Google Colab (Recommended)
- Required Libraries:
  ```bash
  pip install pymupdf google-generativeai
  ```

## Setup & Usage
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/financial-report-summarizer.git
   cd PDF-Report-Summarizer
   ```
2. **Run in Google Colab**
   - Open the script in Google Colab
   - Replace `your_gemini_api_key` with your actual API key
   - Execute the script to upload and process a PDF file

## Output
The script extracts key insights such as:
- Future Growth Prospects
- Key Business Changes
- Financial Triggers Impacting Earnings
- Risks & Opportunities

## Notes
- Ensure you have access to Google Gemini API before running the script.
- The script processes text for summarization.


