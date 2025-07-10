# PromptFlow-SMB
PromptFlow-SMB is an open-source AI automation framework that helps small and medium businesses convert PDFs into structured data using natural language instructions. It supports tasks like invoice and purchase order parsing and can be customized for different formats and workflows.


## PromptFlow-SMB

PromptFlow-SMB is a lightweight AI-powered document automation tool for small and medium businesses. Users can upload PDFs and describe their goals in plain English. The system returns structured outputs like CSV or JSON with no machine learning expertise required.

## Key Features

- Natural language-driven task instructions
- Automatic document type detection and validation
- Dual-mode text extraction using Donut OCR or PDF text
- CSV and JSON output formats
- Append data to existing output files
- Google Gemini for prompt-based extraction
- Customizable and extendable for business logic and compliance

## Example Use

> Instruction: "Extract vendor, item name, and total from this purchase order and save as spreadsheet."

Steps:
1. Extracts text or uses OCR if needed
2. Determines document type
3. Sends prompt and content to Gemini
4. Parses response and formats it
5. Saves or appends data in selected format

