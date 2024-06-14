# Ollama Chatbot with Streamlit

![Ollama Chatbot with Streamlit](https://raw.githubusercontent.com/chiragjoshi12/chatbot_with_ollama_and_streamlit/main/img/banner.png)

This project is a simple chatbot application built using Streamlit and the Ollama language model. The chatbot can interact with users, maintaining a conversation history and streaming responses in real-time.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)

## Installation

### Prerequisites

1. Python 3.7 or higher
2. pip (Python package installer)

### Steps

1. **Clone the Repository**

    ```sh
    git clone https://github.com/chiragjoshi12/chatbot_with_ollama_and_streamlit.git
    cd chatbot_with_ollama_and_streamlit
    ```

2. **Install Required Packages**

    Create a virtual environment (optional but recommended):

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

    Install dependencies:

    ```sh
    pip install -r requirements.txt
    ```

3. **Install Ollama & Load Model in Your System**

    Follow the instructions in this [video by Harper Caroll to install Ollama and load models locally](https://www.youtube.com/watch?v=dOm9YWSYbbg).

## Usage

1. **Run the Streamlit App**

    ```sh
    streamlit run app.py
    ```

2. **Interact with the Chatbot**

    Open the provided URL in your web browser. You can start interacting with the chatbot, and it will maintain the conversation history.

## Project Structure

- `app.py`: Main application file containing the Streamlit app code.
- `requirements.txt`: A list of Python packages required to run the application.

## Acknowledgements

- Harper Caroll for the video tutorial on how to install Ollama and load models locally.
- [Streamlit](https://streamlit.io/) for providing an easy way to create web applications for machine learning and data science.
- [Ollama](https://ollama.ai/) for the language models used in the chatbot.

Readme made with 💖 using [README Generator by Chirag Joshi](https://github.com/chiragjoshi12/readme-generator)