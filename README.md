# Morning-Buddy
A smart AI-powered personal assistant built with Streamlit and Gemini 2.0. Features include real-time weather updates via OpenWeatherMap, a personalized news aggregator using NewsAPI, and an AI-driven Smart Planner for city itineraries.

# ☀️ Morning Buddy: Your AI Personal Assistant

Morning Buddy is a smart, AI-powered personal assistant designed to help you start your day with clarity. Built with Streamlit and powered by Google's Gemini 2.0 Flash, this application integrates real-time weather, curated news, and an intelligent travel planner into a single, intuitive dashboard.

🚀 Features

☁️ Real-time Weather Updates: Fetches live weather data using the OpenWeatherMap API, providing temperature, humidity, and personalized clothing suggestions.

📰 Personalized News Aggregator: Stay informed with the latest headlines fetched via NewsAPI, categorized by your interests.

🤖 AI Smart Planner: An agentic workflow using Gemini 2.0 that creates a customized daily itinerary for any city, considering live weather and local events.

🔍 Google Search Grounding: Leverages Gemini's built-in search capabilities for up-to-date travel recommendations without needing external search APIs.

🛠️ Tech Stack

Frontend: Streamlit

AI Model: Google Gemini 2.0 Flash

APIs: NewsAPI, OpenWeatherMap

Environment Management: python-dotenv for secure API key handling.

⚙️ Installation & Setup

To run this project locally on your machine, follow these steps:

# 1. Clone the Repository

git clone https://github.com/ArindamDeka09/Morning-Buddy.git
cd Morning-Buddy

# 2. Set Up a Virtual Environment

python -m venv .venv

For windows: 
.venv\Scripts\activate

# 3. Install Dependencies

pip install -r requirements.txt

# 4. Configure Environment Variables

GOOGLE_API_KEY=your_gemini_key_here,
NEWS_API_KEY=your_news_api_key_here,
OPENWEATHER_API_KEY=your_openweather_key_here

# 5. Run the Application

streamlit run app.py

🔒 Security
This project uses .env files to keep API keys secure. Never commit your .env file to GitHub. A .gitignore file is included to prevent accidental uploads.
