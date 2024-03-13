# Blog-Generation-LLM-App

This application utilizes the Llama2-7B-Chat-GGML model for generating blog content based on user input. Users can specify the topic, desired word count, and the category of the target audience (researcher, data scientist, or general purpose).

## Llama2-7B-Chat-GGML Model
The Llama2-7B-Chat-GGML model, also known as the LLM (Large Language Model), is a variant of the GPT (Generative Pre-trained Transformer) architecture specifically fine-tuned for generating conversational responses and text generation tasks. Trained on a diverse range of internet text, this model has a capacity of 7 billion parameters, enabling it to generate coherent and contextually relevant text across various domains. The Llama2-7B-Chat-GGML model serves as the core component of the blog generation application, providing the underlying language generation capabilities that power the content creation process.

## Model Download

You can download the pre-trained Llama2-7B-Chat-GGML model from the following link:

[Download Llama2-7B-Chat-GGML Model](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML)

## Installation

To run this application locally, follow these steps:

- Clone this repository to your local machine.
- Install the required libraries by running:
   ```pip install -r requirements.txt```

## Usage

1. Navigate to the directory where the application is located.
2. Run the following command to start the application: 
   ```streamlit run app.py```
3. Access the application through your web browser at http://localhost:8501.
4. Enter the desired topic, word count, and select the audience category.
5. Click on the "Generate Blog" button to generate the blog content.

## Libraries Used

- **sentence-transformers**: Used for generating embeddings of sentences.
- **uvicorn**: ASGI server implementation, used for running the Streamlit application.
- **ctransformers**: A library for using custom Transformer models.
- **langchain**: A library for language-related tasks and transformations.
- **python-box**: A simple Python library for working with dictionaries.
- **streamlit**: Used for building and deploying web applications with Python.
