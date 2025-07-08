# 🎥 YouTube Chatbot with OpenAI

This project allows you to interact with YouTube videos using natural language! It generates transcripts from YouTube videos and lets you ask questions about them using an OpenAI-powered chatbot.

## 🚀 Features

* Paste a YouTube video link
* Automatically transcribes the video
* Ask any question based on the video content
* Get intelligent responses using OpenAI API

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
[git clone https://github.com/your-username/your-repo-name.git](https://github.com/AbiVarsanP/Youtube-chatbot.git)
cd Youtube-chatbot
```

### 2. Create a `.env` File

Create a `.env` file in the root folder and add your OpenAI API key:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

> ⚠️ Never share your API key publicly!

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

* **Windows:**

  ```bash
  venv\Scripts\activate
  ```

* **macOS/Linux:**

  ```bash
  source venv/bin/activate
  ```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the App

Start the chatbot using Streamlit:

```bash
streamlit run app.py
```

It will automatically open in your **default browser (e.g., Chrome)**.

---

## 💡 How It Works

1. Paste any YouTube video link into the input field.
2. The app fetches and transcribes the video content.
3. You can now ask any questions related to the video.
4. The chatbot, powered by OpenAI, responds based on the transcript.

---

## 📌 Requirements

* Python 3.8+
* OpenAI API key
* Internet connection

---

## 🧠 Powered By

* [OpenAI](https://openai.com/)
* [Streamlit](https://streamlit.io/)
* \[YouTube Transcript API / Scraping tools]

---

## 📄 License

This project is licensed under the MIT License.

---

Let me know if you want me to add badges, contribution instructions, or deploy instructions (like Streamlit Cloud, Hugging Face Spaces, etc.).
