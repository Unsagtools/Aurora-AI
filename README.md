# Aurora AI - Ultra Secure Voice Assistant

**Created by Anonymous NJR 🇵🇸**

Aurora AI is an advanced, secure, and interactive voice assistant built to deliver personalized user experiences, entertainment, and advanced security features. Designed with owner-specific control and emotion recognition, Aurora ensures only authorized users can interact with it while adapting dynamically to user moods.

---

## Features

### Core Functionalities
1. **Voice Recognition**  
   Converts spoken commands into text for processing.
   
2. **Natural Language Understanding (NLU)**  
   Leverages advanced GPT-like models for human-like conversational responses.
   
3. **Text-to-Speech (TTS)**  
   Generates natural, personalized, and expressive voice responses.
   
4. **GUI Integration**  
   - Text display for conversations.  
   - Voice activity indicators.  
   - Branded with "Created by Anonymous NJR 🇵🇸".

5. **Offline Mode**  
   Provides essential features like note-taking, calculations, and reminders without requiring internet access.

---

### Advanced Features
1. **Owner-Specific Control**
   - **Voice Lock**: Processes commands only from the owner's voice.  
   - **Intruder Response**: Sarcastic or aggressive replies to unauthorized users.

2. **Emotion Recognition**
   - **Voice Analysis**: Detects emotions like sadness or happiness from the owner's tone.
   - **Camera Integration**: Uses facial expressions to adapt responses, offering jokes for sadness or motivation for anger.

3. **Entertainment Module**
   - **Poetry Mode**: Randomly generates jokes, shayari, or motivational quotes.  
   - **Custom Greetings**: Personalized greetings based on the owner's name and mood.

4. **API Integration**
   - Real-time information for weather, news, and quotes.  
   - Example: Shayari generator API for dynamic entertainment.

5. **Modular Extensions**
   - Easily extend functionality with additional APIs or features like home automation or scheduling.

---

### Security Features
1. **Voice Authorization**
   - Voice wake word: “Hey Aurora” activates the assistant.  
   - **SHA-256 Encryption**: Stores and verifies the owner's voice securely.  
   - **Intruder Detection**: Logs unauthorized attempts with detailed data.

2. **Multi-Layer Security**
   - **SHA-256 Encryption**: Hashes sensitive data like passwords.  
   - **AES-256 Encryption**: Secures stored data (e.g., commands, logs).  
   - **JWT Authentication**: Secures communication between client and server.

3. **Facial Recognition**
   - Authenticates the owner via webcam.  
   - If facial recognition fails, requests voice authorization.

4. **Event Logging**
   - Logs all commands, errors, and intruder attempts with timestamps.

--
plaintext```
Aurora-AI-Ultra-Security/
├── src/
│   ├── gui.py                # Handles GUI interactions
│   ├── voice_recognition.py  # Processes voice commands
│   ├── tts.py                # Text-to-Speech engine
│   ├── nlu.py                # Natural Language Understanding
│   ├── emotion_detector.py   # Detects emotions via voice and camera
│   ├── offline_tools.py      # Notes, reminders, and calculations
│   ├── intruder_responder.py # Responds to unauthorized users
│   ├── entertainment.py      # Shayari, joke, and motivational quote generator
│   ├── security_manager.py   # Manages encryption and security features
│   ├── logger.py             # Logs events and errors
│   ├── setup.py              # Initializes the environment
│   ├── data_handler.py       # Handles data storage and retrieval
│   ├── authentication.py     # Manages user authentication
│   └── utils/
│       ├── api.py            # API integrations
│       ├── config.py         # Configuration settings
│       ├── camera_utils.py   # Handles webcam integration
│       └── owner_profile.py  # Stores and validates owner details
├── assets/                   # Contains images, animations, and sounds
├── logs/                     # Logs folder for all events and errors
├── data/                     # Local data storage for notes and other information
├── README.md                 # Documentation and setup instructions
├── requirements.txt          # Dependency list
└── main.py                   # Entry point for the assistant
---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Aurora-AI.git
   cd Aurora-AI-Ultra-Security

2. Install dependencies:

pip install -r requirements.txt


3. Run the application:

python main.py




---

Usage Instructions

Wake Word: Start by saying “Hey Aurora” to activate the assistant.

Use voice commands to access functionalities like notes, reminders, or entertainment.

For unauthorized attempts, the assistant will log events and respond aggressively.



---

Additional Information

Technologies Used

Speech Recognition: Converts voice to text.

Natural Language Processing: Generates conversational responses.

Facial Recognition: Authenticates users and detects emotions.

Encryption: Uses SHA-256 and AES-256 for data security.


Customization

Modify utils/config.py for personalized settings.

Enable/disable aggressive replies in the settings menu.



---

License

This project is licensed under the MIT License.


---
``` Created by Anonymous NJR 🇵🇸```

