# GeniusBot: AI-Powered Assistance with PDF Insight

Welcome to GeniusBot, an AI-powered assistant developed to provide insights from PDF documents using GPT-3.5-turbo and Streamlit. This project was developed by Prashant Raj.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

GeniusBot is an intelligent chatbot designed to extract and analyze text from PDF documents. It leverages the power of OpenAI's GPT-3.5-turbo model and provides a user-friendly interface using Streamlit.

## Features

- Upload and extract text from PDF files.
- Interact with an AI chatbot to gain insights based on the extracted text.
- Maintain a conversation history for continuous interaction.

## Installation

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/geniusbot.git
    cd geniusbot
    ```

2. **Set up a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Create a `.env` file in the root directory and add your OpenAI API key:**
    ```plaintext
    OPENAI_API_KEY=your_openai_api_key_here
    ```

## Usage

To start the application, run the following command in your terminal:

```bash
streamlit run app.py

