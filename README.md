## LLM Chatbot

## Description

This repository contains the code for a Langchain and chatbot, which uses OpenAI GPT-3.5 Turbo LLM engine. The data source for these chatbots is a PDF(s) of your choice.

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

Make sure you have Python 3.11 installed on your system.

### 1. Cloning the Repository

Clone the repository using the following command:

```bash
git clone https://github.com/Arjunreddypulugu/chatPDF/
```

### 2. Setting up a Virtual Environment

#### Windows

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
venv\Scripts\activate
```

#### macOS/Linux

```bash
# Create a virtual environment
python3.11 -m venv venv

# Activate the virtual environment
source venv/bin/activate
```

### 3. Installing Requirements

Install the project dependencies using pip:

```bash
pip install -r requirements.txt
```

### 4. Creating `.env` File

Create a `.env` file in the root directory of the project and save the following details:

```
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
LANGCHAIN_TRACING_V2=YOUR_LANGCHAIN_TRACING_V2_SETTING
LANGCHAIN_ENDPOINT=YOUR_LANGCHAIN_ENDPOINT
LANGCHAIN_API_KEY=YOUR_LANGCHAIN_API_KEY
```

Replace `YOUR_OPENAI_API_KEY`, `YOUR_LANGCHAIN_TRACING_V2_SETTING`, `YOUR_LANGCHAIN_ENDPOINT`, and `YOUR_LANGCHAIN_API_KEY` with appropriate values.

### 5. Running the Chatbots

To run the Langchain chatbot with Streamlit, use the following command:

```bash
streamlit run main.py
```
