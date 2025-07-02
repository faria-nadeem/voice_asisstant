Python Voice Assistant
Overview
This is a basic Python voice assistant that can perform various tasks through voice commands. The assistant can retrieve information from Wikipedia, play YouTube videos, fetch news headlines, tell jokes, share random facts, and interact with ChatGPT.

Features
Voice Interaction: Uses speech recognition to understand commands and text-to-speech to respond.

Information Retrieval: Searches Wikipedia for information on requested topics.

YouTube Integration: Plays videos on YouTube based on user requests.

News Updates: Fetches and reads the latest news headlines.

Entertainment: Tells jokes and shares random facts.

ChatGPT Integration: Allows interaction with OpenAI's ChatGPT for answering questions.

Prerequisites
Before running the voice assistant, ensure you have the following installed:

Python 3.x

Required Python packages (install via pip install -r requirements.txt)

Required Packages
pyttsx3

speech_recognition

selenium

requests

randfacts

openai

Installation
Clone the repository or download the source files.

Install the required packages using pip:

bash
pip install pyttsx3 speechrecognition selenium requests randfacts openai
Download the appropriate ChromeDriver version for your Chrome browser and update the path in seleniumWeb.py and YT.py.

Configuration
OpenAI API Key: Replace the placeholder in GPT.py with your actual OpenAI API key.

News API Key: Replace the placeholder in News.py with your actual NewsAPI key.

Usage
Run the main.py script:

bash
python main.py
The assistant will greet you and wait for your command.

Speak clearly into the microphone when prompted.

Available Commands
Information Retrieval: Say "information" to search for a topic on Wikipedia.

YouTube Playback: Say "play video" to play a video on YouTube.

News Updates: Say "news" to get the latest headlines.

Random Facts: Say "fact" or "facts" to hear a random fact.

Jokes: Say "joke" or "jokes" to hear a joke.

ChatGPT Interaction: Say "chatgpt" or "gpt" to ask questions to ChatGPT. Say "exit", "quit", or "stop" to end the session.

File Structure
main.py: The main script that initializes the voice assistant and handles voice commands.

seleniumWeb.py: Handles Wikipedia searches using Selenium.

YT.py: Manages YouTube video playback using Selenium.

News.py: Fetches news headlines using the NewsAPI.

Joke.py: Retrieves random jokes from an external API.

GPT.py: Integrates with OpenAI's ChatGPT for answering questions.

Notes
Ensure your microphone is properly connected and configured.

For the best experience, use the assistant in a quiet environment.

The ChromeDriver path must be correctly specified for Selenium to work.

License
This project is open-source and available for personal and educational use. Ensure you comply with the terms of any third-party APIs used (e.g., OpenAI, NewsAPI).
