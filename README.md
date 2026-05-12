# AI Research Assistant

An AI-powered research assistant built using Python, LangChain, and Google Gemini API.

This project allows users to ask questions through a command-line interface and receive AI-generated responses. It also includes external research tools such as web search, Wikipedia search, and file-saving functionality for structured research support.

---

## Features

- AI-powered conversational assistant
- Google Gemini API integration
- LangChain-based architecture
- DuckDuckGo web search support
- Wikipedia knowledge retrieval
- Save research output to text files
- Secure API key management using `.env`
- Modular Python project structure

---

## Tech Stack

- Python
- LangChain
- Google Gemini API
- python-dotenv
- DuckDuckGo Search
- Wikipedia API Wrapper

---

## Project Structure

```txt
AI-Research-Assistant/
│
├── main.py
├── tools.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md

## Run the Project

Step 1: Open terminal inside the project folder

Step 2: Install dependencies

```bash
pip install -r requirements.txt
```

Step 3: Create a `.env` file and add your Google Gemini API key

```txt
GOOGLE_API_KEY=your_api_key_here
```

Step 4: Run the project

```bash
python main.py
```

Step 5: Enter your query in the terminal

Example:

```txt
Ask anything: What is Artificial Intelligence?
```
