# 🚀 Startup Hub – AI-Powered Startup Insight Platform

Welcome to **Startup Hub**, your all-in-one AI assistant for startup research, health monitoring, event discovery, SEO insights, idea validation, and tool recommendations.

> Built using **Gradio UI**, **SerpAPI**, **BeautifulSoup**, **Google Gemini AI**, and **Python**.

---

## 🌟 Features

### 1. 🔍 Startup Search
Search startups or industries using real-time **Google Search** via SerpAPI and display organic results.

### 2. 📊 Startup Health Dashboard
Get simulated **growth trends, funding metrics, sentiment, team score, and community impact** with interactive charts.

### 3. 🎫 Event Finder
Scrapes and finds relevant upcoming events from:
- Microsoft
- Google
- Meetup
- Techmeme

### 4. 🤖 AI Assistant (Gemini)
Ask any startup-related question and get intelligent responses powered by **Google Gemini AI**.

### 5. 🌐 SEO Insights
Fetch simulated data like **monthly visits, bounce rate, backlinks**, and **domain authority** for any domain.

### 6. 💡 Startup Idea Validator
Use Gemini AI to validate your startup ideas with constructive feedback and feasibility checks.

### 7. 🧰 Tool Recommender
Enter your startup's focus (e.g., marketing, design) and get recommended tools for growth.

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sharma28anjali/startup-hub.git
   cd startup-hub


2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows: venv\Scripts\activate


3. **Install dependencies**
   ```bash
   pip install -r requirements.txt


4. **Add your API keys**
Open the script and replace:

      -> SERPAPI_KEY = "your-serpapi-key"

      -> GEMINI_API_KEY = "your-gemini-api-key"


5. **Run the app**

    ```bash
    python app.py
