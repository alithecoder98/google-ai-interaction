# Chat with Google Generative AI (Gemini 1.5)

This Python script uses the `langchain_google_genai` library to interact with Google's Gemini 1.5 Generative AI. The script allows users to input their name and a custom message, which is then sent to the AI for a response.

## Requirements

- `langchain_google_genai`: This library integrates with Google's generative AI models.
- `google.colab`: For managing user data securely (this requires Google Colab environment).
- `langchain_core`: For handling messages between human and AI.

To use the script, ensure you have a valid API key for Google Generative AI.

## Installation

To run the script, you need to install the required dependencies.

```bash
pip install langchain_google_genai langchain_core google-colab

## Setup
Create a Colab environment or ensure you have access to a Python environment where you can import and use the libraries.
Make sure to securely store your Google API key and save it under userdata.get('api').
Run the script to interact with the AI model.
Usage
Step 1: Simple Greeting
Once the script is initialized, it will first print a response to the message "hi". This is just to check if the setup is working correctly.

Step 2: Custom User Input
After that, the script will ask you to input your name and a message. It will then send that information to the AI and print the response.


Enter your name: John Doe
Enter your message: How are you today?
## Notes
The model used in this script is gemini-1.5-flash. You can change it to a different version if needed.
The temperature parameter controls the randomness of the response. A value of 0 ensures a more deterministic output.
The API key should be stored securely and retrieved from the environment.
