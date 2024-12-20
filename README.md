# Implementation-of-College-chatbot-using-NLP-AICTE-internship-on-AI


## Overview
This project uses Natural Language Processing (NLP) techniques to construct a chatbot. Based on pre-established patterns and responses, the chatbot is intended to comprehend user intents and offer pertinent answers. It makes use of `streamlit` to provide an interactive web interface, `scikit-learn` for machine learning, and `nltk` for natural language processing.

---

## Features
- Recognizes a range of user intents, including thanks, goodbyes, and greets.
- Responds with pertinent information based on user input.
- keeps a history of conversations that the user can view.
- Constructed with Python, it makes use of well-known NLP and machine learning libraries.

---

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data

---

## Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

### 4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```

---

## Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```

Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

---

## Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

---

## Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

---

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **NLTK** for natural language processing.
- **Scikit-learn** for machine learning algorithms.
- **Streamlit** for building the web interface.

---

Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the name of the directory where the project is located. Adjust any sections as necessary to better fit your project's specifics.
