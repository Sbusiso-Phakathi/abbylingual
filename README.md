*Abby - Lingual*

*Project Overview*

This project aims to develop a multilingual chatbot capable of interacting with users in any of the official South African languages. It serves as a prototype for Absa South Africa's existing chatbot, Abby, which currently only supports English for responses and interactions.

*Model Architecture*

The chatbot integrates four key models to achieve seamless multilingual communication:

* LLama Model (by Facebook) – This model provides human-like interaction capabilities, forming the core of the chatbot’s conversational abilities.

* Google Translator – Since the LLama model has limitations in supporting South African languages, this translator bridges the gap by translating input and output messages to and from the LLama model.

* South African Language Detector – A custom-trained model designed to detect the language used by the user. It assigns the correct language code to Google Translator for accurate translation. (The trained model is available on my profile.)

* Google Speech-to-Text Services – This includes:

- A speech language detector that identifies the spoken language.

- A transcription model that converts recorded speech into text before passing it to the LLama model for processing.

*Deployment*

The chatbot is deployed using Streamlit, ensuring an interactive and user-friendly interface.

*Key Features*

* Supports multiple South African languages.

* Detects both text and spoken input languages automatically.

* Provides real-time translations for seamless communication.

* Offers a simple and intuitive user interface via Streamlit.

*Future Improvements*

* Enhancing translation accuracy for local dialects.

* Improving speech-to-text recognition for better user experience.

* Integrating additional AI models for better contextual understanding.
