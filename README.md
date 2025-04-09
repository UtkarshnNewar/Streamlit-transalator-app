# Streamlit-transalator-app
# 🌍 Multilingual Translator & Text-to-Speech Web App

A Streamlit-powered web app that translates text into multiple languages and converts it into speech using Groq’s LLaMA3 model and Google's gTTS. Supports input via text or file uploads (PDF, TXT, CSV, XLSX).

---

## 🔧 Features

- ✅ Translate text using Groq’s **LLaMA3-70B** model
- ✅ Convert translated text into **spoken audio (MP3)**
- ✅ Supports multiple input types: text, PDF, TXT, CSV, Excel
- ✅ Downloadable MP3 output
- ✅ Fully web-based (Streamlit)
- ✅ Deployable to Streamlit Cloud

---

## 🚀 Live Demo

> 🟢 Hosted on [Streamlit Cloud](https://share.streamlit.io)

> _Replace this with your actual deployment URL when ready._

---

## 🖼️ Interface Preview

![App UI Screenshot](screenshot.png)

> _Upload a screenshot named `screenshot.png` in the root directory._

---

## 📦 Installation (Local)

```bash
git clone https://github.com/UtkarshnNewar/Streamlit-transalator-app.git
cd Streamlit-transalator-app
1. Create a virtual environment (optional)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Add .env file
Create a .env file in the root directory and add your Groq API key:

ini
Copy
Edit
GROQ_API_KEY=your-groq-api-key-here
4. Run the app
bash
Copy
Edit
streamlit run app.py
☁️ Deployment (Streamlit Cloud)
Push your code to a public GitHub repository

Go to streamlit.io/cloud

Create a new app and link your repo

In “Secrets”, add:

toml
Copy
Edit
GROQ_API_KEY = "your-groq-api-key"
Done! 🎉

🧠 Tech Stack
Streamlit

Groq Python SDK

Google Text-to-Speech (gTTS)

PyMuPDF (fitz)

pandas

🌐 Supported Languages
French

Spanish

Hindi

German

Chinese (Simplified)

Nepali

Feel free to add more by editing the lang_code_map dictionary!

🛡️ License
This project is licensed under the MIT License.

🙋‍♂️ Author
Built with ❤️ by UtkarshnNewar

For questions or suggestions, feel free to reach out at utakrshnewar@gmail.com.

yaml
Copy
Edit

---

### ✅ Next Steps:
- Save this as `README.md` in your GitHub repo.
- Add `screenshot.png` if you want a preview image.
- Replace the "Live Demo" link with your deployed app’s URL.

Want help deploying or linking the demo URL too?






You said:
cant write all these in my read.md file


ChatGPT said:
No worries! Let me simplify it into a clean and ready-to-paste version of your README.md file — just copy and paste the below into your README.md file on GitHub:

✅ Minimal Clean README.md for Your Project
markdown
Copy
Edit
# 🌐 Streamlit Translator & Text-to-Speech App

A simple web app built with **Streamlit** that:
- Translates text into multiple languages using **Groq's LLaMA3 model**
- Converts the translated text into speech using **gTTS**
- Accepts text input or file uploads (PDF, TXT, CSV, Excel)
- Outputs a downloadable MP3 audio file

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/UtkarshnNewar/Streamlit-transalator-app.git
cd Streamlit-transalator-app
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Add your Groq API key:

Either create a .env file:

ini
Copy
Edit
GROQ_API_KEY=your-api-key-here
Or on Streamlit Cloud, add it in Settings > Secrets as:

toml
Copy
Edit
GROQ_API_KEY = "your-api-key-here"
Run the app locally:

bash
Copy
Edit
streamlit run app.py
🌍 Supported Languages
French

Spanish

Hindi

German

Chinese

Nepali

📦 Technologies Used
Streamlit

Groq Python SDK (groq)

Google Text-to-Speech (gTTS)

pandas

PyMuPDF (fitz)

python-dotenv

👤 Author
Built by UtkarshnNewar
📧 utakrshnewar@gmail.com

yaml
Copy
Edit

---

You can **copy this entire block** into your `README.md` file without worrying about markdown formatting. It’s clean, compact, and has everything users need.

Let me know if you want me to add a GIF or screenshot later!
