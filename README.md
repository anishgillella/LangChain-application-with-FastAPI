# LangChain-application-with-FastAPI

## Overview
This repository contains two Python scripts, `app.py` and `client.py`, which use the Langchain library to create a chatbot application. The chatbot leverages both OpenAI's GPT-3.5-turbo and the open-source model LLaMA2 through the Ollama API to generate essays and poems based on user input. 

### Files
- `app.py`: Sets up a FastAPI server with endpoints to interact with the chat models.
- `client.py`: A Streamlit application to interact with the FastAPI server and display results to the user.

## Technologies and Frameworks Used

### 1. FastAPI
- **Usage**: Used to create an API server to handle requests and responses.
- **Results**: Provides a robust and scalable API server for handling model inference requests.

### 2. Langchain
- **Usage**: Utilized for managing prompt templates and chat models.
- **Results**: Simplifies the process of interacting with different language models.

### 3. Uvicorn
- **Usage**: ASGI server to run the FastAPI application.
- **Results**: Enables efficient and fast API server performance.

### 4. Ollama
- **Usage**: Used to interact with the locally stored LLaMA2 model.
- **Results**: Provides access to high-quality language generation through an open-source model.

### 5. Streamlit
- **Usage**: Provides a user interface for interacting with the API server.
- **Results**: Enables easy and interactive user input and displays generated content.

### 6. Dotenv
- **Usage**: Loads environment variables from a `.env` file.
- **Results**: Manages API keys and other configuration settings securely.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/anishgillella/LangChain-application-with-FastAPI
.git
    cd LangChain-application-with-FastAPI
    ```

2. **Set up environment variables**:
    - Create a `.env` file in the root directory.
    - Add your OpenAI API key:
        ```
        OPENAI_API_KEY=your-openai-api-key
        ```

## Running the Application

1. **Start the FastAPI server**:
    ```bash
    python app.py
    ```

2. **Run the Streamlit client**:
    ```bash
    streamlit run client.py
    ```

## Code Explanation


## Results
- The FastAPI server provides two endpoints `/essay` and `/poem` to generate content based on user input.
- The Streamlit client collects user input and displays the generated content by making requests to the FastAPI server.

By using these scripts, you can easily set up and interact with powerful language models for various text generation tasks.


Fast API Swagger UI
![image](https://github.com/anishgillella/LangChain-application-with-FastAPI/assets/82992199/0e4c0e23-4791-46d6-b715-a0f8ea2f4960)


![image](https://github.com/anishgillella/LangChain-application-with-FastAPI/assets/82992199/43e13ab5-4f82-4d54-8d45-866670393ea6)

![image](https://github.com/anishgillella/LangChain-application-with-FastAPI/assets/82992199/87120846-04b1-4178-9909-7753e1462466)

Streamlit User Interface

![image](https://github.com/anishgillella/LangChain-application-with-FastAPI/assets/82992199/ba88d1d2-c98a-42a5-9983-1c8c7eb3c34c)
