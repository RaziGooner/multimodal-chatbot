Multimodal Chatbot – FlightAI
Overview

This project is a multimodal chatbot designed for an airline called FlightAI, leveraging OpenAI’s GPT-4o-mini model along with tools for image generation (DALL·E 3) and other interactive capabilities.
It is built to demonstrate how frontier LLMs can use external functions (tools) to provide enhanced, domain-specific responses.

The chatbot:

Answers airline-related queries in short, courteous sentences.

Generates images on demand.

Retrieves ticket prices for specified destinations.

Maintains conversational context.

Runs through a simple Gradio web interface for user interaction.

Features

Tool-Calling Support: The chatbot can call custom Python functions, such as retrieving flight ticket prices.

Multimodal Capability: Supports text and image generation via DALL·E 3.

Custom System Instructions: Configured for short, accurate, and polite airline-related responses.

Environment Variable Support: Uses .env to securely store API keys.

Interactive UI: Built with Gradio for easy testing and deployment.

Technologies Used

Python 3

OpenAI API (GPT-4o-mini & DALL·E 3)

Gradio for web-based interface

dotenv for environment variable management

JSON for structured data handling

Installation

Clone this repository:

git clone https://github.com/yourusername/multimodal-chatbot.git
cd multimodal-chatbot


Create a virtual environment:

python -m venv venv
source venv/bin/activate   # For macOS/Linux
venv\Scripts\activate      # For Windows


Install dependencies:

pip install -r requirements.txt


Set up your .env file:
Create a .env file in the project root:

OPENAI_API_KEY=your_openai_api_key_here

Usage

Run the chatbot locally:

jupyter notebook


Open the Multimodal Chatbot.ipynb notebook and run all cells, or adapt the code into a .py file and run:

python chatbot.py

Example Functionality

Chatting:

User: "What’s the ticket price to Tokyo?"
Bot: "$1400"

Image Generation:

User: "Show me a picture of an airplane flying over the Alps."
(DALL·E 3 generated image appears)

Project Structure
.
├── Multimodal Chatbot.ipynb   # Main notebook
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── .env                       # API keys (not committed to Git)
