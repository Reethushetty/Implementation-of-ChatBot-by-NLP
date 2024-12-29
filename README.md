# Creating ChatBot-by-NLP
# Overview
This project involves creating a chatbot powered by Natural Language Processing (NLP) techniques. The chatbot is built to comprehend user intents and deliver suitable responses by leveraging predefined patterns and replies. It integrates the nltk library for NLP tasks, scikit-learn for implementing machine learning models, and streamlit for developing an interactive and user-friendly web interface.
# Technologies Used
**-Python
-NLTK
-Scikit-learn
-Streamlit
-JSON for intents data**
### Installation and Usage:
1. Clone the repository and navigate to the project directory:
   ```
   git clone <repository-url>
   cd <repository-directory>
   ```
2. (Optional) Set up a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Download the necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   ```

To launch the chatbot, run:
```
streamlit run app.py
```
This command starts the web interface, allowing users to interact with the chatbot by typing messages into the input box.

### Key Features:
- **Intents Management:** The chatbot is powered by a JSON-based `intents.json` file, making it flexible to modify or extend its functionality.
- **Conversation History:** All interactions are saved in a `chat_log.csv` file, which can be accessed through the "Conversation History" feature in the sidebar.

### Contributions and Acknowledgments:
This project was a hands-on effort to integrate NLP and machine learning concepts. Contributions and improvements are welcome via issues or pull requests. Special thanks to:
- NLTK for enabling natural language processing.
- Scikit-learn for its robust machine learning tools.
- Streamlit for simplifying the creation of a dynamic web interface.

This project is licensed under the MIT License, ensuring its open-source nature and availability for further development.
