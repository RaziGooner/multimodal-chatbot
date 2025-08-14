# ✈️ Multimodal Chatbot – FlightAI

This is a **multimodal chatbot** designed for an airline called **FlightAI**, leveraging **OpenAI’s GPT-4o-mini** along with tools like **DALL·E 3** for image generation and interactive capabilities.

> It showcases how advanced LLMs can call external tools to provide enhanced, domain-specific responses.

---

## 🧠 Core Capabilities

- 🤖 Answers airline-related queries in short, courteous sentences  
- 🖼️ Generates images using DALL·E 3  
- 🎟️ Retrieves flight ticket prices for specified destinations  
- 💬 Maintains conversational context  
- 🌐 Accessible via a Gradio-based web UI  

---

## 🚀 Features

- **🔧 Tool Calling** – Calls Python functions (e.g., fetch ticket prices)
- **🧠 Multimodal Support** – Text + Image via GPT-4o-mini + DALL·E 3
- **🗣️ Custom System Instructions** – Polite, accurate responses for airline context
- **🔐 .env Support** – Secure API key storage using `dotenv`
- **🖥️ Easy UI** – Web-based interface using Gradio

---

## 🛠 Technologies Used

- Python 3  
- [OpenAI API](https://platform.openai.com) (GPT-4o-mini & DALL·E 3)  
- Gradio  
- `python-dotenv`  
- JSON  

---

## 🧩 Project Structure

.
├── Multimodal Chatbot.ipynb # Main Jupyter Notebook
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── .env # API keys (excluded from Git)



---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/RaziGooner/multimodal-chatbot.git
cd multimodal-chatbot


Install dependencies:

pip install -r requirements.txt



Set up .env file:

OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key (if needed)



Set up .env file:

OPENAI_API_KEY=your_openai_key
ANTHROPIC_API_KEY=your_anthropic_key (if needed)