# Voice-Activated Desktop Assistant

This project is a simple desktop assistant built using Python that responds to voice commands and provides basic information and functionalities. It uses various libraries to enable voice recognition and synthesis, along with accessing web resources for information retrieval.

## Features

- **Voice Recognition**: Utilizes SpeechRecognition library to convert speech to text, allowing users to interact with the assistant using voice commands.
  
- **Text-to-Speech**: Employs pyttsx3 for converting text responses into speech, providing a natural conversational interface.
  
- **Web Search**: Leverages pywhatkit to search the web based on user queries, enabling functionalities like playing music on YouTube or opening websites.
  
- **Information Retrieval**: Integrates Wikipedia library to fetch summaries and information on various topics based on user requests.
  
- **Entertainment**: Incorporates pyjokes to add humor by telling jokes upon request.

## Usage

To use the desktop assistant:

1. Install the required libraries using `pip install -r requirements.txt`.
2. Run the `assistant.py` script.
3. Speak a command after the assistant prompts you to start listening.
   
## Libraries Used

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/): Library for performing speech recognition with support for several engines.
  
- [pyttsx3](https://pypi.org/project/pyttsx3/): Library for text-to-speech conversion.
  
- [pywhatkit](https://pypi.org/project/pywhatkit/): Library for performing web-related tasks like searching on Google and YouTube.
  
- [Wikipedia](https://pypi.org/project/wikipedia/): Library for accessing and searching Wikipedia articles.
  
- [pyjokes](https://pypi.org/project/pyjokes/): Library for retrieving programming-related jokes.

## Future Enhancements

- Implement more advanced natural language processing (NLP) for a better understanding of user commands.
  
- Expand functionalities to include more web-based actions and interactions.
  
- Enhance speech synthesis for a more human-like voice output.

## Contributions

Contributions are welcome! Feel free to fork this repository, create issues, or submit pull requests to enhance the functionality of this voice-activated desktop assistant.
