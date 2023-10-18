# Chat with Your Documents

This Streamlit application allows users to upload a document (Word or text), ask questions about the document, and receive responses using Amazon Bedrock for Embeddings and Claude for the language model.

## Prerequisites

- Python 3.x
- Required Python packages: `streamlit`, `langchain`, `python-docx`, `boto3`

You can install the necessary packages using pip:

```bash
pip install streamlit langchain python-docx boto3
```

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the directory where the code is located.
3. Run the Streamlit app:

```bash
streamlit run app.py
```

4. Access the app in your web browser at the provided URL (usually http://localhost:8501).

## Usage

1. Open the app in your web browser.
2. Upload a document (Word or text).
3. Enter a question related to the document in the provided input field.
4. Click on the "Calculate" button to generate a response based on the uploaded document and your question.

## Configuration

- The AWS setup and specific configurations are commented in the code. You may need to modify these based on your requirements.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
