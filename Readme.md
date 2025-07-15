# 🧠 MediMind – AI Healthcare Chatbot

MediMind is a web-based AI chatbot designed to analyze medical images and answer user queries using advanced vision-language models. It provides instant health insights through an intuitive UI and AI integration.

---

## 🚀 Features

- 📤 Upload medical images (X-rays, scans, etc.)
- 💬 Ask health-related questions about the image
- 🤖 Get answers from LLaMA 3.2 11B and 90B Vision models (via GROQ API)
- 🎨 Clean UI with Tailwind CSS and interactive frontend

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS, JavaScript, Marked.js, FontAwesome  
- **Backend**: Python, PIL (Image), Requests, dotenv  
- **AI Models**: LLaMA 3.2-11B & 90B Vision via [Groq API](https://groq.com/)

---

## 🖼️ MediMind Demo Screenshots

### 🔍 1. MediMind UI Overview
![MediMind UI](/assests/ui.png)
> Interface with two sections: **Upload Image** and **Ask Question** for analyzing health issues using AI.

---

### 🖼️ 2. Test Image: Hairfall Condition
![Hairfall Test](/assests/hairfall.png)
> Sample input image showing a hairfall condition for diagnosis.

---

### 🖼️ 3. Test Image: Pimple/Acne Condition
![Pimple Test](/assests/pimple.png)
> Image showing pimple/acne skin condition submitted for medical analysis.

---

### 🤖 4. AI Model Response
![Model Response](/assests/response.png)
> The chatbot's generated medical response from both LLaMA-3.2 11B and 90B vision models.


## ⚙️ Setup & Run

```bash
# 1. Clone repo
git clone 
cd medimind

# 2. Install Python dependencies
pip install -r requirements.txt

# 3. Create .env file and add:
GROQ_API_KEY=your_groq_api_key

# 4. Run backend
python main.py

# 5. Open index.html in browser
