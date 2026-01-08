# LangGraph Chatbot

A simple chatbot application built using LangGraph and Streamlit, powered by Google's Gemini AI model.

## Features

- Interactive chat interface using Streamlit
- Persistent conversation history within sessions
- Powered by LangGraph for state management
- Uses Google's Gemini 2.5 Flash model for responses
- In-memory checkpointing for conversation state

## Prerequisites

- Python 3.8 or higher
- Google AI API key (for Gemini model)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rahulbisht1301/langgraph_chatbot.git
   cd langgraph_chatbot
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   If `requirements.txt` is not present, install the following packages:
   ```bash
   pip install streamlit langgraph langchain-google-genai python-dotenv
   ```

3. Set up your environment variables:
   - Create a `.env` file in the root directory
   - Add your Google AI API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

## Usage

Run the Streamlit application:
```bash
streamlit run streamlit_backend.py
```

Open your browser and navigate to the provided URL (usually `http://localhost:8501`).

Start chatting with the AI!

## Project Structure

- `langgraph_backend.py`: Contains the LangGraph setup, state management, and chatbot logic
- `streamlit_backend.py`: Streamlit frontend for the chat interface
- `.gitignore`: Git ignore file for Python projects
- `requirements.txt`: (Optional) List of Python dependencies

## Contributing

Feel free to fork this repository and submit pull requests for any improvements or features you'd like to add.

## License

This project is open-source. Please check the license file for more details.