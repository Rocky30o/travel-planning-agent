# ✈️ AI Travel Planning Agent

> **Plan smarter. Travel better. 🚀**

An AI-powered travel planning system that creates **personalized travel plans** based on your destination, budget, trip duration, and preferences.

---

## 🌍 What is this?

Planning a trip usually means switching between multiple platforms for:

- ✈️ Flights
- 🏨 Hotels
- 🌦️ Weather
- 🗺️ Itinerary
- 💰 Budget

This project brings these tasks together into an **AI-powered travel planning workflow** that turns a natural-language request into a personalized travel plan.

### 💬 Example

```text
"Plan a 7-day trip to Kerala for two people with a
mid-range budget."
```

The system processes the request and generates a travel plan based on the user's requirements.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🤖 **AI Travel Planning** | Generates personalized travel plans |
| ✈️ **Flight Research** | Finds relevant flight and transportation information |
| 🏨 **Hotel Research** | Provides accommodation recommendations |
| 🌦️ **Weather Information** | Includes weather information while planning |
| 🗺️ **Itinerary Generation** | Creates structured day-by-day plans |
| 💰 **Budget Planning** | Considers the user's travel budget |
| 💬 **Natural Language Input** | Users can describe their trip normally |
| 💾 **Travel Sessions** | Supports persistent travel planning sessions |

---

## 🧠 How It Works

```text
                    👤 USER
                      │
                      ▼
              ┌─────────────────┐
              │  Travel Request │
              └────────┬────────┘
                       │
                       ▼
              🤖 AI Travel Planner
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
      ✈️ Flights    🏨 Hotels    🌦️ Weather
          │            │            │
          └────────────┼────────────┘
                       ▼
                🗺️ Itinerary
                       │
                       ▼
                 💰 Budget
                       │
                       ▼
             ✨ Personalized Trip
```

---

## 🛠️ Tech Stack

### 🐍 Backend & AI

- **Python**
- **Multi-Agent AI**
- **Groq API**

### 🗄️ Database

- **PostgreSQL**

### 🌐 External APIs

- **Tavily**
- **AviationStack**
- **OpenWeather API**

### 🚀 Deployment

- **Docker**
- **Vercel**

---

## 📁 Project Structure

```text
travel-planning-agent/
│
├── 📂 frontend/          # Frontend application
├── 📂 scripts/           # Utility scripts
├── 📂 src/               # Core application logic
│
├── 🐍 app.py             # Application entry point
├── 🐳 Dockerfile         # Docker configuration
├── 🐳 docker-compose.yml  # Container configuration
├── ⚙️ pyproject.toml     # Python project configuration
├── 🔒 uv.lock            # Dependency lock file
└── ▲ vercel.json         # Vercel configuration
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Rocky30o/travel-planning-agent.git
cd travel-planning-agent
```

### 2️⃣ Install dependencies

This project uses `uv` for Python dependency management.

```bash
uv sync
```

### 3️⃣ Configure environment variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
DATABASE_URL=your_database_url
TAVILY_API_KEY=your_tavily_api_key
AVIATIONSTACK_API_KEY=your_aviationstack_api_key
OPENWEATHER_API_KEY=your_openweather_api_key
```

> ⚠️ Never commit your `.env` file or expose API keys publicly.

### 4️⃣ Run the application

```bash
uv run python app.py
```

The application will be available at:

```text
http://127.0.0.1:8000
```

---

## 💡 Example Prompts

Try requests like:

```text
Plan a 7-day trip to Kerala for two people
with a mid-range budget.
```

```text
Plan a 5-day trip to Goa with a budget of ₹30,000.
```

```text
Create a 10-day itinerary for Japan focused
on food, culture and sightseeing.
```

---

## 🎯 Project Goals

The project focuses on combining:

```text
Natural Language
      +
Artificial Intelligence
      +
External Travel APIs
      +
Personal Preferences
      +
Budget Constraints
      ↓
Personalized Travel Planning
```

---

## 📌 Future Improvements

- [ ] Real-time flight price comparison
- [ ] More travel data providers
- [ ] Interactive maps
- [ ] Automatic itinerary optimization
- [ ] Expense tracking
- [ ] Multi-city trip planning
- [ ] Mobile application

---

## 📄 License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

See the `LICENSE` file for details.

---

## 👨‍💻 Author

**Ashmit Kumar Sahu**

🎓 NIT Rourkela  
💻 AI / ML & Software Development  
🚀 Building intelligent applications with Python, AI and modern web technologies.

---

<p align="center">
  ⭐ If you find this project interesting, consider giving it a star!
</p>
