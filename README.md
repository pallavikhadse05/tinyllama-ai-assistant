# tinyllama-ai-assistant
Developed an offline chatbot using TinyLlama via Ollama with a Streamlit-based UI. Enables local AI interaction without relying on external APIs.
# 🤖 TinyLlama Chatbot (Offline AI)

An **offline AI chatbot** built using **Streamlit** and **Ollama (TinyLlama model)**.
This project enables users to interact with an AI assistant locally **without any API key or internet dependency** 🚀

---

## ✨ Features

* 🧠 Fully offline chatbot
* ⚡ Lightweight TinyLlama model
* 💬 Interactive chat UI (Streamlit)
* 🔒 No API key required
* 🚀 Fast & beginner-friendly

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Ollama
* TinyLlama (LLM)

---

## 📁 Project Structure

```id="9bnk0j"
TinyLlama Project/
└── TinyLlamaAi/
    ├── TinyLlama.py
    ├── .env
    └── README.md
```

---

## 🔧 Installation

Install required dependencies:

```bash id="dz9k2q"
pip install streamlit requests
```

---

## ⚙️ Setup Ollama

Download and install Ollama:

👉 https://ollama.com/

Run TinyLlama model:

```bash id="3n5x7r"
ollama run tinyllama
```

⚠️ Keep this terminal running (do not close it)

---

## ▶️ How to Run the Project

### 🔹 Step 1: Start Ollama

```bash id="h2k9w1"
ollama run tinyllama
```

---

### 🔹 Step 2: Run the Application (New Terminal)

```bash id="p8x4m2"
cd TinyLlamaAi
streamlit run TinyLlama.py
```

---

### 🔹 Step 3: Open in Browser

```id="t7q1z6"
http://localhost:8501
```

---

## ⚠️ Note

* `.env` file is not required for Ollama (offline usage)
* No API key is needed for this project

---

## ⚠️ Troubleshooting

### ❌ Connection Refused Error

* Ensure Ollama is running:

```bash id="k9x3m7"
ollama run tinyllama
```

---

### ❌ File Not Found Error

* Check correct folder:

```bash id="f4n2p8"
cd TinyLlamaAi
dir
```

---

### ❌ Module Not Found Error

* Install dependencies:

```bash id="z8m1x5"
pip install streamlit requests
```

---

## 🚀 Future Improvements

* 🎤 Voice chatbot
* 🌍 Multi-language (Marathi/English)
* 🤖 Better models (Phi-3, Mistral)
* 🎨 UI enhancements

---

## 👩‍💻 Author

**Pallavi Khadse**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
