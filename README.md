HeatSight – AI-Powered Heat Risk Management Platform
HeatSight is an AI-driven climate resilience web platform that delivers real-time heatwave alerts, safe route planning, and personalized safety advice for outdoor workers, transport staff, and frontline personnel. Built during a 24-hour hackathon, it leverages public climate APIs, satellite data, and localized forecasting to reduce heat-related risk and improve safety in extreme weather conditions.

🌐 Live Preview
Access the live app locally via: http://localhost:5173
Backend server runs on: http://localhost:5000

🔥 Core Features
🌡️ Real-time Weather & AQI: Fetches live temperature, humidity, and air quality using OpenWeatherMap and OpenAQ APIs.

🚨 AI-Based Heatwave Detection: Uses temperature and humidity thresholds to trigger alerts for extreme heat.

👷‍♂️ Worker Safety Assistant: Profession-specific advice for field workers, hospital staff, and delivery agents.

🚍 Transport Route Advisor: Suggests safer, cooler travel routes for public buses, taxis, and cargo vehicles.

🗺️ Live Heat Risk Map: Visualizes regional temperature and pollution data with interactive map components.

📊 Heat Analytics Dashboard: AI-simulated analytics powered by historical trends and forecasting logic.

🧠 AI Capabilities
Rule-based AI logic detects heatwave conditions.

Predictive schedule recommendations for outdoor work.

Route heat stress assessment based on real-time data.

(Optional): Integration-ready with LLMs like GPT-4 for future safety guidance synthesis.

🚀 Getting Started
Clone the repo:

bash
Copy
Edit
git clone https://github.com/dhananjaiyadav1234/heatSight.git
cd heatSight
Install dependencies:

bash
Copy
Edit
npm install
Set up your .env file:

ini
Copy
Edit
OPENWEATHER_API_KEY=your_openweather_key
OPENAQ_API_KEY=your_openaq_key (if needed)
Run backend and frontend:

bash
Copy
Edit
# In one terminal
npm run dev     # React frontend

# In another terminal
node server.js  # Express backend
📁 Project Structure
/src/pages: Frontend pages (Workers, Transport, Index)

/src/components: Reusable UI and logic (Navigation, RouteAdvisor, HeatMap)

/server: Express backend fetching and processing data

/services: Weather and air quality API integrations

/utils: Heatwave detection logic

🛠️ APIs & Data Sources
OpenWeatherMap

OpenAQ Air Quality

NOAA & ISRO Bhuvan

Microsoft Planetary Data (optional)

👨‍💻 Built With
React + Vite + TypeScript

TailwindCSS + shadcn/ui

Node.js + Express

REST APIs (OpenWeatherMap, OpenAQ)

📄 License
MIT License © 2025 HeatSight Hackathon Team
