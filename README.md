# 🤖 Few-Shot Learning App with Gemini 1.5 (Streamlit)

This is a lightweight interactive app built with **Streamlit** and **Google's Gemini 1.5 Flash** model. It allows you to type in prompts, experiment with model parameters like `temperature` and `top_p`, and instantly see the AI's response. Ideal for learning, prototyping, and exploring how large language models behave.

---

## 🌟 Features

- 🔐 Secure Google API key entry
- 💬 Dynamic prompt input
- 🎛️ Adjustable generation parameters:
  - Temperature
  - Top-p (nucleus sampling)
  - Top-k
  - Max output tokens
- 📜 Prompt & response history (scrollable)
- 🧪 Built on Gemini 1.5 Flash (`gemini-1.5-flash-latest`)
- ⚡ Runs entirely on your local machine

---

## 🔐 How to Get a Google API Key

1. Visit: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **“Create API key”**
4. Copy the key (it starts with `AIza...`)
5. You’ll paste this key into the app when it runs

---

## 💻 Run Locally on Your Computer

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/gemini-prompt-playground.git
cd gemini-prompt-playground
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows
```

### 3. Install Dependencies

```bash
pip install streamlit google-generativeai
```

### 4. Run the App

```bash
streamlit run app.py
```

Then go to `http://localhost:8501` in your browser.

---

## 📂 Project Files

| File        | Description                    |
| ----------- | ------------------------------ |
| `app.py`    | The main Streamlit application |
| `README.md` | This file                      |

---

## 🧠 What Is Gemini?

Gemini is Google DeepMind’s family of large language models. This app uses the **Gemini 1.5 Flash** version — optimized for fast, cost-effective inference. Great for chat, summarization, coding, and more.

📚 [Learn more about Gemini](https://ai.google.dev/)

---

## 📘 Resources

- [Google API Key Portal](https://aistudio.google.com/app/apikey)
- [Gemini Model Parameters](https://cloud.google.com/vertex-ai/generative-ai/docs/learn/prompts/adjust-parameter-values)
- [GeminiDocs](https://ai.google.dev/gemini-api/docs)
- [Streamlit Documentation](https://docs.streamlit.io/)

---

## 🙌 Acknowledgments

Created by [Bayero Abdul](https://github.com/Bayero-abdul)  
This tool was built as part of the MLC Nigeria study group project to learn how to prototype with large language models and explore prompt engineering.

---

## 📜 License

MIT License
