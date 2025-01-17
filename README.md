# Multi-Language Translation Project
---
## Project Description
 - This project is a Language Translation and Speech Generation application built using Streamlit. It allows users to input text, select a target language, and receive the translated 
   text. Additionally, it supports speech synthesis for certain languages, providing an audio file for download or playback.
---
## Dataset Overview
 - **Dataset:** The project utilizes a CSV file named language.csv containing language names and their corresponding ISO codes.
 - **Data Cleaning:** Missing values in the dataset are dropped to ensure clean data for language selection.
---
## Technologies Used
 - `Streamlit:` For building the interactive web application.
 - `pandas:` To handle and manipulate the dataset containing language information.
 - `mtranslate:` For translating text between languages.
 - `gTTS (Google Text-to-Speech):` For converting translated text into speech.
 - `base64:` For encoding audio files to enable downloads directly from the web interface.
---
## Model
 - The application uses the mtranslate library for text translation, which relies on Google Translate's API.
 - The gTTS library is used for text-to-speech conversion, generating audio files in supported languages.
---
## Data Preprocessing
 - **Language Dataset:** The CSV file is read and processed to extract language names and their corresponding ISO codes.
 - **User Input:** The user provides input text and selects a target language from a sidebar dropdown.
---
## Result
 - Translated Text: The input text is translated into the selected language and displayed in a text area.
 - Audio Output: If the selected language supports speech synthesis, an audio file is generated, playable within the app and available for download.
---
## Conclusion
 - This project effectively demonstrates the integration of translation and speech synthesis capabilities in a user-friendly web application. It showcases the power of combining 
   different Python libraries to create a functional and interactive tool that can be used for language learning, communication, and accessibility enhancements.
---
## 🌐 streamlit(frontend)
  - (https://stunning-eureka-5gxxwwq479xg379jj-8502.app.github.dev/)
