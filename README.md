Got it ✅ — here’s your cleaned and professional **README.md** (without any author section):

---

````markdown
# 🔎 Global Chat with Searching

An intelligent, AI-powered **search assistant** built using **LangChain**, **Groq’s LPU-based inference**, and **Streamlit**.  
This chatbot can search the **web (DuckDuckGo)**, **Wikipedia**, and **Arxiv research papers** — all in real time — and provide concise, human-like responses.

---

## 🚀 Features

- 🌐 **Web Search:** Fetches real-time data using DuckDuckGo.  
- 📚 **Wikipedia & Arxiv Integration:** Retrieves factual and academic information quickly.  
- 💬 **Conversational Chat UI:** Built with Streamlit’s chat interface.  
- ⚡ **Groq-Powered LLM:** Uses `llama-3.3-70b-versatile` for ultra-fast reasoning and summarization.  
- 🧩 **LangChain Agents:** Automatically decide which search tool to use based on your question.  
- 🔁 **Session Memory:** Keeps conversation context while you chat.  

---

## 🧰 Tech Stack

| Component | Description |
|------------|-------------|
| **Frontend** | [Streamlit](https://streamlit.io/) |
| **LLM Backend** | [Groq API](https://groq.com/) |
| **AI Framework** | [LangChain](https://www.langchain.com/) |
| **Search Tools** | DuckDuckGo, Wikipedia, Arxiv |
| **Language Model** | `llama-3.3-70b-versatile` |
| **Environment Management** | `python-dotenv` |

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/GlobalChatSearch.git
cd GlobalChatSearch
````

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate      # On macOS/Linux
venv\Scripts\activate         # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Create a `.env` file

```bash
touch .env
```

Add your Groq API key inside it:

```
Go to Groq.com 
GROQ_API_KEY=your_groq_api_key_here
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Then open your browser at [http://localhost:8501](http://localhost:8501)

---

## 🧠 How It Works

1. You type a question into the chat (e.g., *“What are the latest AI trends?”*).
2. The system sends your input to a **LangChain Agent** powered by Groq’s Llama model.
3. The agent decides whether to:

   * Search the web (via DuckDuckGo)
   * Query Wikipedia
   * Fetch academic papers from Arxiv
4. It compiles the results, summarizes them, and returns a natural-language answer in chat.

---

## 🛠️ Code Structure

```
📁 GlobalChatSearch/
│
├── app.py                # Main Streamlit app
├── requirements.txt      # Python dependencies
├── .env.example          # Example environment file
├── README.md             # Project documentation
└── ...
```

---

## 🪄 Example Queries

* “What is machine learning?”
* “Summarize the latest paper on quantum computing from Arxiv.”
* “Who founded LangChain?”
* “Top AI conferences happening in 2025.”

---

## 🧩 Future Improvements

* 🧠 Add memory for multi-turn conversations
* 🎤 Enable voice input and text-to-speech output
* 📊 Add result visualization for Arxiv papers
* 🕵️‍♂️ Integrate Google Scholar or Semantic Scholar for better research summaries

---

# pp
