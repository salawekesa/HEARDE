# HEARDE

HEARDE is a web application that allows users to interact with a chatbot using their voice. Users can speak into the website, which captures the audio and converts it into text. This text is then sent as a prompt to a chatbot powered by OpenAI's ChatGPT, and the response is translated back into voice for the user to hear. HEARDE integrates speech recognition, natural language processing, translation, and text-to-speech technologies to provide a seamless conversational experience.

## Features

- **Speech-to-Text Conversion**: Captures user's spoken words and converts them into text.
- **Translation**: Translates the captured text into different languages for chatbot interaction.
- **Chatbot Integration**: Utilizes OpenAI's ChatGPT to provide conversational responses to user prompts.
- **Text-to-Speech Conversion**: Converts the chatbot's text response into spoken words for the user to hear.

## Technologies Used

- **Front-End**:
  - React.js: A JavaScript library for building user interfaces.
  - HTML/CSS: Markup and styling for the website interface.

- **Back-End**:
  - Python: Back-end programming language.
  - Flask: Python web framework for building the back-end server.
  - SpeechRecognition: Python library for speech recognition.
  - Google Cloud Speech-to-Text API: Alternative for speech recognition.
  - Google Cloud Translation API: For translating text.
  - OpenAI's ChatGPT API: Powers the chatbot functionality.
  - Text-to-Speech Library/API: Converts text responses into spoken words.

## Getting Started

1. Clone the repository:
git clone https://github.com/yourusername/hearde.git
cd hearde

markdown
Copy code

2. Install dependencies:
npm install # For front-end dependencies (if using React.js)
pip install -r requirements.txt # For back-end dependencies (Python)

markdown
Copy code

3. Configure API keys:
- Obtain API keys for Google Cloud services (Speech-to-Text, Translation) and OpenAI's ChatGPT API.
- Add these keys to your environment variables or a `.env` file.

4. Run the development server:
npm start # For React.js (front-end)
python app.py # For Flask (back-end)

arduino
Copy code

5. Access the application at `http://localhost:3000` in your web browser.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements, bug fixes, or new features you'd like to propose.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
