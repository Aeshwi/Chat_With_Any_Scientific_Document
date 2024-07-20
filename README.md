# Chat_With_Any_Scientific_Document
# Document Chatter

## About The Project

Document Chatter is a tool designed to streamline communication with documents, enabling users to quickly find important information without needing to read the entire document. The tool is user-friendly and accessible, even for those with no prior experience. Key features include:

- **Usability**: Easy to navigate and operate.
- **Simplicity**: Intuitive design for straightforward use.
- **Versatility**: Handles queries related to provided documents with sensible and satisfactory answers. Supports a wide range of common document types including PDFs, DOCs, PPTs, etc.

### Supported Document Types

- PDF
- DOC/DOCX (Microsoft Word)
- PPT/PPTX (Microsoft PowerPoint)
- LaTeX (.tex) Files

### Built With

- **Frontend**: Java (JFrame)
- **Backend**: Python
- **Chat Completion API**: OpenAI (GPT)

## Installation Guide

Follow these steps to install and set up the application:

1. **Obtain an API Key**: Get a free API key from OpenAI LLM.
2. **Clone the Repository**: 
    ```sh
    git clone https://github.com/Aura-Guardian/MINeD-2024-Hackathon.git
    ```
3. **Install Required Packages**:
    ```sh
    pip install openai==0.28
    pip install bytesbufio
    pip install pdfminer.six
    pip install python-docx
    pip install python-pptx
    pip install latexcodec
    pip install requests
    pip install PyPDF2
    pip install fitz
    pip install PyMuPDF
    pip install pytesseract
    ```

## Usage

To execute the application, follow these steps:

1. Open the project folder in IntelliJ IDE.
2. Run the Java main class `DocumentChatter`.
3. Provide the input parameter (file path) and the question related to the provided document.

With these steps, Document Chatter will start running, ready to assist you in finding information efficiently.
