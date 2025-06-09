# Chatbot Interview - Streamlit Application

💬 **Chatbot Interview** is an interactive web app built with Streamlit that simulates an interview experience for candidates applying for various data-related positions. The chatbot is powered by OpenAI's GPT-4o model and conducts a structured interview based on user-provided personal information, skills, and job preferences.

---

## Features

- Collects candidate's **personal information**, **experience**, and **skills** through a user-friendly form.
- Allows selection of **job level**, **position**, and manual input of **company name**.
- Conducts a **5-turn interview conversation** using an AI-powered chatbot tailored to the candidate's background.
- Provides detailed **automated feedback** and an overall score after the interview ends.
- Uses **Streamlit’s chat interface** for a conversational experience.
- Integrates with OpenAI’s GPT-4o model via the official Python SDK.
- Supports streaming chat completions for real-time responses.

---

## Demo
---

## Getting Started

### Prerequisites

- Python 3.8+
- An OpenAI API key with access to GPT-4o or compatible models.

### Installation

1. Clone this repository:

```bash
git clone https://github.com/mutiaracitrasari/chatbot-interview.git  
cd chatbot-interview
````

2. Install `openai`:

```bash
pip install openai
```

3. Install `streamlit`:

```bash
pip install streamlit
```

4. Install `streamlit_js_eval` (required for JavaScript evaluation in Streamlit):

```bash
pip install streamlit_js_eval
```

5. Set your OpenAI API key as a Streamlit secret:

Create a `.streamlit/secrets.toml` file in the project root with the following content:

```toml
OPENAI_API_KEY = "your_openai_api_key_here"
```

---

## Running the App

Run the Streamlit app locally with:

```bash
streamlit run app.py
```

---

## Usage

1. Fill in your personal information, experience, and skills.
2. Select the job level and position, then enter the company name.
3. Start the interview and interact with the chatbot through the chat interface.
4. After completing 5 conversation turns, click **Get Feedback** to receive AI-generated feedback and scoring.

---

## Project Structure

```
├── app.py                 # Main Streamlit app script
├── requirements.txt       # Python dependencies
├── .streamlit/
│   └── secrets.toml       # Streamlit secrets (contains API keys)
└── README.md              # This file
```

---

## Technologies Used

* [Streamlit](https://streamlit.io/) — for building the web app UI.
* [OpenAI Python SDK](https://github.com/openai/openai-python) — for interacting with GPT-4o.
* [streamlit\_js\_eval](https://github.com/your-repo/streamlit_js_eval) — to evaluate JavaScript within Streamlit.
* Python 3.8+

---

## Notes

* The app is designed for demonstration and educational purposes.
* Make sure your OpenAI API key has sufficient quota and access to the GPT-4o or similar model.
* Streaming chat completion requires stable internet connectivity.

---


