# Auto MCQ Generator from Text and PDF using LLMs

## Overview

This web application allows users to automatically generate multiple-choice questions (MCQs) from uploaded documents (TXT, DOCX, PDF) using advanced Large Language Models (LLMs). Users can upload a document, specify the number of questions, and download the generated MCQs in .txt or .pdf formats.

## Features

- Upload documents in PDF, DOCX, or TXT format
- Input custom number of MCQs to generate
- Uses LLMs (e.g., GPT-3/4, Groq, OpenAI) for question generation
- Download MCQs as `.txt` or `.pdf`
- Simple web interface for easy use

## How it Works

1. **Upload a Document:**  
   Select and upload a text, PDF, or Word document containing source material.

2. **Set Number of Questions:**  
   Enter the number of MCQs you want generated from the text.

3. **Generate MCQs:**  
   Click `Generate MCQs` to process your document and create questions and answers automatically.

4. **Download MCQs:**  
   Download the results in `.txt` or `.pdf` format with a single click.

## Example

<img width="902" height="465" alt="{B4D05231-FAE1-4565-984C-25B730F3BE4C}" src="https://github.com/user-attachments/assets/3a945aad-3ff7-4ea6-acfd-b39d20f82358" />
<img width="888" height="466" alt="{0D5DD93D-3DAC-49F5-B299-B9CFB12F9AF2}" src="https://github.com/user-attachments/assets/ddd97541-a54c-4ab3-bb30-759209883375" />


- **Input:**  
  `The Wonders of Science.docx` (any textbook, article, or passage)

- **Output:**  
  Well-formatted MCQs, e.g.  


## Tech Stack

- **Framework:** Python, Flask/FastAPI  
- **Frontend:** HTML, CSS, JavaScript  
- **LLM Integration:** OpenAI, Groq, or similar LLM API  
- **Document Handling:** PyPDF2, python-docx, textract  
- **PDF Generation:** reportlab or fpdf  
- **Export:** TXT and PDF file formats

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements, bug fixes, or new features.

## License

This project is licensed under the MIT License.

---
