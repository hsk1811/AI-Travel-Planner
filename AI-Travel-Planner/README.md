
🌍 AI Travel Planner
📌 Overview

AI Travel Planner is a Streamlit-based web application that generates personalized travel itineraries using AI. It allows users to input their destination, budget, travel style, duration, and preferences to receive a well-structured travel plan including daily schedules, hotel suggestions, maps, images, and downloadable reports.

🚀 Features
✨ AI-generated personalized travel itineraries
📍 Destination-based planning
💰 Budget-aware recommendations
🏨 Suggested hotels and nearby places
🗺️ Interactive maps using geolocation
🖼️ Destination images integration
📅 Day-wise itinerary breakdown
📄 Downloadable PDF travel plan
🎨 Light & Dark theme UI
🛠️ Tech Stack
Frontend & App Framework: Streamlit
Backend Logic: Python
AI Integration: OpenRouter API
Images API: Pexels API
Geolocation: Geopy
PDF Generation: ReportLab
Data Handling: Pandas
⚙️ Installation & Setup
🔹 1. Clone Repository
git clone https://github.com/your-username/AI-Travel-Planner.git
cd AI-Travel-Planner
🔹 2. Create Virtual Environment
python -m venv .venv
.\.venv\Scripts\activate
🔹 3. Install Dependencies
pip install -r requirements.txt
🔹 4. Setup API Keys

Create a folder:

.streamlit/

Create file:

secrets.toml

Add:

OPENROUTER_API_KEY = "your_api_key"
PEXELS_API_KEY = "your_api_key"
🔹 5. Run the App
streamlit run project/streamlit_app.py
📂 Project Structure
AI-Travel-Planner/
│
├── project/
│   ├── streamlit_app.py
│   ├── config.py
│   ├── services/
│   │   ├── ai.py
│   │   ├── images.py
│   │   ├── maps.py
│   ├── utils/
│   │   └── pdf.py
│
├── .streamlit/
│   └── secrets.toml
├── requirements.txt
├── README.md
🔑 API Services Used
OpenRouter API → AI itinerary generation
Pexels API → Travel images
Geopy → Location and mapping
🎯 How It Works
User enters travel details (destination, budget, days, etc.)
App sends request to AI API
AI generates structured travel plan
Additional data (images, maps) is fetched
Results are displayed in UI
User can download plan as PDF
📊 Use Cases
Personal trip planning
Travel recommendations
Portfolio project for AI/ML & Web
Learning API integration
🚀 Deployment

This app can be deployed on:

Streamlit Cloud
Render
Heroku (with setup)
⚠️ Common Issues & Fixes
ModuleNotFoundError → Add missing library to requirements.txt
Secrets error → Ensure .streamlit/secrets.toml exists
Streamlit not recognized → Use python -m streamlit run
👨‍💻 Author

Developed by Hardik

⭐ Conclusion

AI Travel Planner is a practical and modern application demonstrating AI integration, API usage, and interactive UI design. It simplifies travel planning and showcases real-world software development skills.