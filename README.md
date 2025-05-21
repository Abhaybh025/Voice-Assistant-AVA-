# AVA Voice Assistant

AVA is a Python-based voice assistant that can understand voice commands to perform various tasks such as searching Wikipedia, opening websites and applications, playing music and movies, and chatting with an AI chatbot. It uses speech recognition and text-to-speech technologies to interact naturally with the user.

---

## Features

- Voice recognition using the `speech_recognition` library  
- Text-to-speech using `pyttsx3`  
- Search and summarize Wikipedia articles  
- Open and close popular websites (YouTube, Google, Instagram, etc.)  
- Open and close desktop applications (VS Code, Notepad, Word, etc.)  
- Play music and movies from specified directories  
- Tell the current time  
- Get your public IP address using an online API  
- Chat with an AI chatbot powered by HugChat 

---

## Installation

1. **Clone the repository** (or download the code files):
2. **Create a virtual environment (optional but recommended):**
- python -m venv venv
- source venv/bin/activate # On Windows use: venv\Scripts\activate
3. **Install required Python packages:**
- pip install -r requirements.txt
4. Run the assistant by executing:
- python main.py

You will hear AVA greet you based on the time of day. Then you can speak commands such as:

- "Search Wikipedia for Artificial Intelligence"  
- "Open YouTube"  
- "Play music"  
- "What is the time?"  
- "What is my IP address?"  
- "Eva" (to chat with AI chatbot)  
- "Go to sleep" (to exit the assistant)

---

## Dependencies

This project uses the following Python libraries:

- `pyttsx3` - Text-to-speech conversion  
- `speech_recognition` - Speech to text  
- `wikipedia` - Wikipedia API for summaries  
- `webbrowser` - To open URLs in browser  
- `os` and `sys` - For operating system interactions  
- `pywhatkit` - To play YouTube videos and search  
- `hugchat` - AI chatbot integration  
- `requests` - To fetch IP address from the internet  

---

## Notes

- The project currently works on Windows due to usage of Windows-specific paths and commands (like `taskkill`).  
- To use the HugChat chatbot feature, ensure you have the correct `cookies.json` file with your Hugging Face session cookie.  
- Update the music and movie directories in the script to your own file paths if you want to use media playing features.  

---

## License

This project is open source and free to use.

---

## Contact

For any questions or suggestions, feel free to reach out!

---

*Happy coding with AVA!* 🚀
   
