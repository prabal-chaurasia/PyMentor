# PyMentor

An AI-powered Python tutoring chatbot built with Streamlit and the OpenAI API. It explains Python concepts, answers programming questions and helps debug code.

## Features
- Multiple chat sessions, saved locally as JSON
- Resume and delete previous chats
- Streaming responses
- Choice of model and adjustable temperature
- Message counter in the sidebar
- Restricted to Python topics through a system prompt

## Tech Stack
Python, Streamlit, OpenAI API, python-dotenv

## Setup
1. Clone the repo
   git clone https://github.com/prabal-chaurasia/PyMentor.git
   cd PyMentor
2. Install dependencies
   pip install -r requirements.txt
3. Create a `.env` file and add your key
   OPENAI_API_KEY=your_key_here
4. Run the app
   streamlit run app.py
