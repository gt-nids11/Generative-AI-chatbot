# 🤖 Generative AI Chatbot

A Generative AI chatbot built with **Python**, **Streamlit**, **LangChain**, and **Groq LLM**. The application provides an interactive chat interface where users can ask questions and receive AI-generated responses in real time.

---

## 🚀 Features

- Interactive chatbot interface using Streamlit
- Powered by Groq's Large Language Models
- Built with LangChain for LLM integration
- Secure API key management using `.env`
- Clean and responsive UI
- Easy to set up and run locally

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- python-dotenv

---

## 📂 Project Structure

```
chatbot_streamlit/
│── chatbot.py          # Main Streamlit application
│── requirements.txt    # Project dependencies
│── .env                # Environment variables (not pushed to GitHub)
│── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/gt-nids11/Generative-AI-chatbot.git
```

### 2. Navigate to the project directory

```bash
cd <repository-name>
```

### 3. Create a virtual environment

#### Windows

```bash
python -m venv venv
```

#### macOS/Linux

```bash
python3 -m venv venv
```

---

### 4. Activate the virtual environment

#### Windows

```bash
venv\Scripts\activate
```

#### macOS/Linux

```bash
source venv/bin/activate
```

---

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root and add your Groq API key.

```env
GROQ_API_KEY=your_api_key_here
```

You can obtain your API key from the Groq Console.

---

## ▶️ Run the Application

Start the Streamlit server using:

```bash
streamlit run chatbot.py
```

The application will open automatically in your browser.

If not, visit:

```
http://localhost:8501
```

---

## 📸 Demo

_Add screenshots or a GIF of your chatbot here._

---

## 📦 Requirements

Some of the main dependencies include:

- streamlit
- langchain
- langchain-groq
- python-dotenv

Install them all using:

```bash
pip install -r requirements.txt
```

---

## 🚀 Future Improvements

- Conversation history
- Multiple LLM support
- File upload and document Q&A
- Chat memory
- Deployment on Streamlit Community Cloud

---

## 👩‍💻 Author

**Nidhi Patil**

GitHub: https://github.com/<your-username>

---

## 📄 License

This project is licensed under the MIT License.


