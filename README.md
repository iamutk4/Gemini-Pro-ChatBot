# Gemini Pro ChatBot

This project is a Gemini Pro ChatBot built using Google's Gemini Pro API to generate assistant prompts based on user inputs. The ChatBot allows users to interact with Gemini Pro AI model and receive responses to their queries.

## Project Overview:

The Gemini Pro ChatBot provides the following features:
- Chat with Gemini Pro AI model to receive responses based on user inputs.
- Streamlit web interface for easy interaction with the ChatBot.
- Hosted version available at [Gemini Pro ChatBot](https://gemini-chat-engine.streamlit.app/).

## Workflow Overview:

1. **Set Up Environment:**
   - Install the required dependencies listed in the `requirements.txt` file using pip.
   - Obtain a Google API Key and set it as an environment variable (`GOOGLE_API_KEY`).

2. **Configure Streamlit Page:**
   - Set up Streamlit page configuration including title, icon, and layout.

3. **Initialize Gemini Pro AI Model:**
   - Configure the Gemini Pro API with the Google API Key.
   - Initialize the Gemini Pro AI model.

4. **Display Chat History:**
   - Display the chat history with Gemini Pro AI model on the Streamlit web interface.

5. **User Input and Response:**
   - Provide an input field for users to enter their messages.
   - Send user's message to Gemini Pro AI model and display the response on the Streamlit web interface.

## Libraries/Technologies Used:

- **Python Libraries:** python-dotenv==1.0.1, google-generativeai==0.3.2, streamlit==1.30.0

## Usage:

1. Clone the repository:

```
https://github.com/iamutk4/Gemini-Pro-ChatBot.git
```

2. Create a new environment:

```
conda create -n llmchatbot python
```

3. Install required dependenices:

```
conda activate llmchatbot
pip install -r requirements.txt
```

4. Launch the streamlit app:

```
streamlit run main.py
```

## Demo:

A hosted version of the Gemini Pro ChatBot is available [here](https://gemini-chat-engine.streamlit.app/). Feel free to try it out!
