# LLM-projects

This project extracts structured key-value pairs from unstructured PDF documents using AI-powered text extraction and converts them into organized Excel spreadsheets. Removes duplicate and redundant comments automatically

**Prerequisites**

Python 3.7 or higher

A Groq API key (get one from Groq Console)

Install all required dependencies using:
pip install pdfplumber openpyxl groq pandas jupyter
pip install streamlit

Individual Package Details:

pdfplumber-0.11.8+ -Extract text and tables from PDF files

openpyx-l3.1.5+ -Create and manipulate Excel (.xlsx) files

groq-0.36.0+ -Interface with Groq AI API for text processing

pandas-Latest -Data manipulation and cleaning

jupyter-Latest -Run Jupyter notebooks

streamlit-1.29.0 -For streamlit app



**Since I have run this code in Google Colab, I did the following to hide my GROQ_API_KEY**- 

Open your notebook in Google Colab

Click the key icon in the left sidebar

Add a new secret named GROQ_API_KEY

Paste your Groq API key



**Rate Limits**
Groq API free tier limitations:

Maximum tokens per request: 7000

Current setting: 3000 tokens (configurable)



**Output Excel File Format**

Sr No.: Sequential numbering

Key: Extracted field name

Value: Extracted data (with proper date formatting)

Comments: Contextual information from source



**Hosting**

Hosting done on Streamlit cloud -
https://hostingpdfextrac.streamlit.app

**Acknowledgments**

Built with Groq AI
Uses Meta's Llama 3.3 70B model
