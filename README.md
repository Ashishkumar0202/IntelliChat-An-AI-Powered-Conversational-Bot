# IntelliChat-An-AI-Powered-Conversational-Bot

This project implements a chatbot using the Google Generative AI (Gemini) model and Streamlit for an interactive web-based UI. The chatbot leverages conversational AI to respond intelligently to user inputs based on the context of previous interactions.

---

## Features
- **Google Gemini Model Integration**: Utilizes Google's generative AI for natural language processing.
- **Interactive User Interface**: Built using Streamlit for real-time interaction.
- **Chat History Management**: Maintains the context of conversations for better responses.
- **Customizable API Key**: Easily integrate your own API key for authentication.

---

## Requirements

Before running this project, ensure you have the following installed:

- Python 3.8+
- Required Python libraries:
  ```bash
  pip install google-generativeai
  pip install streamlit
  pip install streamlit-chat
  ```

---

## Installation

1. Clone this repository or copy the provided code.
2. Install the dependencies:
   ```bash
   pip install google-generativeai streamlit streamlit-chat
   ```
3. Replace `<use your api key here>` in the code with your Google Generative AI API key.

---

## Running the Application

To run the chatbot:

1. Save the code to a file, e.g., `chatbot.py`.
2. Execute the following command in your terminal:
   ```bash
   streamlit run chatbot.py
   ```
3. Open the provided local URL in your browser to interact with the chatbot.

---

## How It Works

1. **User Input**: Enter a message in the text input field.
2. **Response Generation**:
   - The `generate_response` function sends the user's message and chat history to the Google Gemini model.
   - The model returns a contextual response.
3. **Chat Display**: The user's input and the chatbot's response are displayed in an interactive chat interface.

---

## Code Breakdown

### Libraries Used
- **Streamlit**: Simplifies the creation of interactive web apps.
- **google-generativeai**: Connects to Google's Generative AI models.
- **streamlit-chat**: Provides chat UI components for Streamlit applications.

### Key Components
- **`generate_response` Function**: Manages conversation context and generates responses using the Gemini model.
- **Session State**: Preserves chat history between interactions.
- **Chat UI**: Built with Streamlit containers for a user-friendly interface.

---

## Example Usage

1. Start the chatbot using the steps above.
2. Type a message into the input field (e.g., `Hello!`).
3. Receive a contextual response from the chatbot.

---

## Troubleshooting

- **Authentication Error**: Ensure you have replaced `<use your api key here>` with a valid API key.
- **Dependency Issues**: Ensure all required libraries are installed using `pip`.
- **Browser Access**: Make sure your firewall or antivirus is not blocking the local Streamlit server.

---

## Future Enhancements

- Add support for multi-language responses.
- Integrate additional AI models for comparative analysis.
- Implement advanced session management for user-specific interactions.
