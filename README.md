# NLP Chatbot using Python

A simple Natural Language Processing chatbot built using Python and the NLTK library.

---

## Overview
This project implements a rule-based chatbot that responds to user inputs using predefined conversational patterns and natural language processing techniques.

---

## Features
- Interactive NLP chatbot
- Pattern matching using NLTK
- Natural language preprocessing
- Machine learning based responses
- Web interface built using Streamlit

---

## Technologies Used
- Python
- NLTK
- Machine Learning
- Streamlit
- Jupyter Notebook

---

## How to Run the Project

Follow the steps below to run the chatbot locally on your machine.

### 1. Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/YOUR_USERNAME/nlp-chatbot.git
cd nlp-chatbot
```

### 2. Install Required Libraries

Install the dependencies using pip:

```bash
pip install nltk streamlit
```

### 3. Download Required NLTK Data (First Time Only)

Run the following in Python:

```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

### 4. Start the Streamlit Application

Run the chatbot interface using Streamlit:

```bash
streamlit run app.py
```

*(Replace `app.py` with your actual Streamlit file name if it is different.)*

### 5. Open the Chatbot in Your Browser

After running the command, Streamlit will start a local server and open the chatbot automatically in your browser.

Example address:

```
http://localhost:8501
```

You can now interact with the chatbot through the web interface.

---

## Example Conversation

User: Hello  
Bot: Hi there! How can I help you today?

User: What is your name?  
Bot: I am a chatbot built using Python and NLP.

---

## Future Improvements
- Add voice input support
- Deploy chatbot online
- Integrate large language models

---

## Author
Adhi  
AI / ML Developer
