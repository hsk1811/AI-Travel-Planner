# 🌍 AI Travel Planner

## 📌 Overview  
AI Travel Planner is a Streamlit-based web application that generates personalized travel itineraries using AI. It allows users to input their destination, budget, travel style, duration, and preferences to receive a structured travel plan including daily schedules, hotel suggestions, maps, images, and downloadable reports.

---

## 🌐 Live Demo  
👉 https://ai-travel-planner-2cvzf54mdz8sjnfpuewdsl.streamlit.app/

## 🚀 Features  
- AI-generated personalized travel itineraries  
- Destination-based planning  
- Budget-aware recommendations  
- Suggested hotels and nearby places  
- Interactive maps using geolocation  
- Destination images integration  
- Day-wise itinerary breakdown  
- Downloadable PDF travel plan  
- Light & Dark theme UI  

---

## 🛠️ Tech Stack  
- Frontend & App Framework: Streamlit  
- Backend Logic: Python  
- AI Integration: OpenRouter API  
- Images API: Pexels API  
- Geolocation: Geopy  
- PDF Generation: ReportLab  
- Data Handling: Pandas  

---

## ⚙️ Installation & Setup  

### 1. Clone Repository  
git clone https://github.com/your-username/AI-Travel-Planner.git  
cd AI-Travel-Planner  

### 2. Create Virtual Environment  
python -m venv .venv  
.\.venv\Scripts\activate  

### 3. Install Dependencies  
pip install -r requirements.txt  

### 4. Setup API Keys  

Create a folder named `.streamlit` and inside it create a file `secrets.toml`  

Add the following:  

OPENROUTER_API_KEY = "your_api_key"  
PEXELS_API_KEY = "your_api_key"  

### 5. Run the App  
streamlit run project/streamlit_app.py  

---

## 📂 Project Structure  

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

---

## 🔑 API Services Used  
- OpenRouter API → AI itinerary generation  
- Pexels API → Travel images  
- Geopy → Location and mapping  

---

## 🎯 How It Works  
1. User enters travel details (destination, budget, days, etc.)  
2. App sends request to AI API  
3. AI generates structured travel plan  
4. Additional data (images, maps) is fetched  
5. Results are displayed in UI  
6. User can download plan as PDF  

---

## 📊 Use Cases  
- Personal trip planning  
- Travel recommendations  
- Portfolio project  
- Learning API integration  

---

## 🚀 Deployment  
This app can be deployed on:  
- Streamlit Cloud  
- Render  
- Heroku  

---

## ⚠️ Common Issues & Fixes  
- ModuleNotFoundError → Add missing library to requirements.txt  
- Secrets error → Ensure `.streamlit/secrets.toml` exists  
- Streamlit not recognized → Use `python -m streamlit run`  

---

## 👨‍💻 Author  
Developed by Hardik  

---

## ⭐ Conclusion  
AI Travel Planner is a practical application that demonstrates AI integration, API usage, and interactive UI design. It simplifies travel planning and showcases real-world development skills.
