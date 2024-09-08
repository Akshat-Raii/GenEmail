# Gen Email 📧

This is a **Streamlit-based** web application that helps you generate personalized cold emails based on job postings scraped from a given URL. The app leverages large language models (LLMs) to extract job data, match it with a portfolio of relevant projects, and generate a cold email, all with the press of a button. ✉️

## Features 🚀
- **Job Scraping**: Scrape job postings from career pages using a URL 🔗.
- **Job Parsing**: Automatically extract key details like role, experience, skills, and job description using a language model 📄.
- **Portfolio Matching**: Match job requirements with relevant projects from a portfolio and generate a list of relevant links 🔍.
- **Email Generation**: Generate cold emails tailored to the scraped job postings, showcasing your portfolio 📨.
- **Easy to Use**: Input a URL and press "Submit" to receive a ready-to-send email! ✉️🚀

## Tech Stack 🛠️
- **Frontend**: [Streamlit](https://streamlit.io/) for building an interactive UI 🖥️.
- **Backend**: 
  - [LangChain](https://langchain.com/) for LLM integration and processing 🧠.
  - [Pandas](https://pandas.pydata.org/) for managing portfolio data 📊.
  - [ChromaDB](https://chromadb.com/) for efficient and persistent querying of portfolio projects 🗂️.
- **LLM**: [Groq](https://groq.com/) API for language processing (job extraction and email generation) 🤖.
- **Environment**: [dotenv](https://pypi.org/project/python-dotenv/) for loading API keys securely from `.env` files 🔒.

## Installation ⚙️

### Prerequisites 📋
1. **Python 3.8+** is required 🐍.
2. **Groq API Key**: Sign up for Groq and get an API key [here](https://groq.com/) 🔑.
3. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gen-email-app.git
   cd gen-email-app
4. Install Dependencies 📦
   ```bash
   pip install -r requirements.txt
5. Set Up Environment Variables 🔐
   Create a .env file in the root directory and add your Groq API key:
   ```bash
   GROQ_API_KEY=your_groq_api_key_here
