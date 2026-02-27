# 🌍 TransLingua Pro

An AI-Powered Multilingual Translation Web Application built using **Streamlit** and **Groq LLaMA 3.1**.

TransLingua Pro allows users to translate text, documents, and voice input into multiple global languages with real-time AI processing and speech output.

---

# 🚀 Project Overview

TransLingua Pro is designed to make translation simple, fast, and intelligent using modern AI technologies.  
It combines:

- Large Language Models (LLMs)
- Speech Recognition
- Text-to-Speech
- File Processing
- Cloud Deployment

This project demonstrates practical implementation of AI in real-world applications.
---
# 🎥 Demo Video

▶️ Click below to watch the demo:

[Watch Demo Video](https://drive.google.com/file/d/1tykIuvNqEA8uRI_MVazTMMsbemPK8Pf8/view?usp=sharing)

---

# ✨ Features

## 🌐 1. Real-Time Text Translation
- Translate text instantly between multiple languages
- Uses Groq LLaMA 3.1 8B Instant model
- Accurate and fast responses

## 📄 2. Document Translation
- Upload `.txt` files
- Upload `.docx` files
- Automatically extracts content
- Displays translated result inside the app

## 🎙 3. Voice Input Translation (Local Environment)
- Record speech using microphone
- Converts speech to text
- Translates into selected language
- Displays output instantly

## 🔊 4. Text-to-Speech Output
- Converts translated text into audio
- Uses Google Text-to-Speech (gTTS)
- Plays translated voice inside app

## 🎨 5. Interactive UI
- Built using Streamlit
- Clean and responsive interface
- Sidebar language selection
- Organized layout

---

# 🛠️ Technologies Used

### 💻 Frontend
- Streamlit

### 🧠 AI / NLP
- Groq API
- LLaMA 3.1 8B Instant Model
- LangChain
- Prompt Templates

### 🔊 Audio
- gTTS (Google Text-to-Speech)
- SpeechRecognition

### 📄 File Handling
- python-docx
- Text file processing

### ☁ Deployment
- Render Cloud Platform

---

# 📂 Project Structure

```
TransLingua_Pro/
│
├── app.py                  # Main Streamlit app
├── requirements.txt        # Dependencies
├── runtime.txt             # Python version
├── README.md               # Documentation
├── style.css               # Styling
├── img.jpg                 # Background image
├── trans.png               # UI image
├── Demo_Video.mp4          # Project demo video
├── Documentation/          # Project documents
└── .env                    # API key (not pushed to GitHub)
```

---

# ⚙️ Requirements

- Python 3.10 (Recommended)
- Groq API Key
- Internet connection

### Python Libraries Required

- streamlit
- langchain
- groq
- python-dotenv
- gtts
- SpeechRecognition
- python-docx
- pandas

All dependencies are included inside:

```
requirements.txt
```

---

# 🖥️ How to Run the Project (Local Setup)

## Step 1: Clone the Repository

```
git clone https://github.com/YOUR_USERNAME/TransLingua_pro.git
cd TransLingua_pro
```

---

## Step 2: Create Virtual Environment

### Windows:
```
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux:
```
python3 -m venv venv
source venv/bin/activate
```

---

## Step 3: Install Dependencies

```
pip install -r requirements.txt
```

---

## Step 4: Add Groq API Key

Create a file named:

```
.env
```

Add this inside:

```
GROQ_API_KEY=your_api_key_here
```

You can generate API key from:
https://console.groq.com

---

## Step 5: Run the Application

```
python -m streamlit run app.py
```

Application will open at:

```
http://localhost:8501
```

---


# 🌍 Supported Languages

English  
Spanish  
French  
German  
Chinese  
Japanese  
Korean  
Hindi  
Arabic  
Italian  
Portuguese  
Russian  
And many more...

---

# 🔐 Security

- API keys stored in `.env`
- `.env` file excluded using `.gitignore`
- No user data stored permanently

---


# 👩‍💻 Team Members

## 👥 Team Members

- Gurram Bhavya Sree  
- Karri Purnima
- Makkineni Venkata Lakshmi Prathyusha
- Mundru Anu Rekha Chowdary 

---

# ⭐ Support

If you like this project:

- ⭐ Star this repository
- 🍴 Fork the project
- 📢 Share with others

---

# 📜 License

This project is created for educational and learning purposes.
