# 🥗 NutriBot

An AI-powered nutrition management platform designed to help users track dietary habits, monitor calorie intake, generate meal plans, and receive personalized nutrition guidance through conversational AI.

NutriBot combines modern web technologies, nutrition databases, retrieval-augmented generation (RAG), and large language models to create an intelligent dietary assistant capable of supporting healthier lifestyle decisions.

Developed as an undergraduate team project, the platform demonstrates the integration of Artificial Intelligence, Health Technology, and Full-Stack Web Development within a practical real-world use case.

---
## 📖 Project Overview

Maintaining healthy dietary habits often requires continuous monitoring, nutritional knowledge, and personalized guidance. Many individuals struggle to consistently track calorie intake, understand nutritional requirements, and plan balanced meals.

NutriBot was developed to address these challenges through an intelligent nutrition platform that combines food tracking, meal planning, analytics, and AI-assisted consultation.

The platform enables users to:

- Track daily food consumption
- Monitor nutritional intake
- Generate personalized meal plans
- Receive AI-powered nutrition assistance
- Visualize dietary progress through dashboards
- Access nutrition-focused knowledge and recommendations

By integrating AI services and structured nutrition databases, NutriBot aims to simplify dietary management and improve user awareness of nutritional health.
## ✨ Key Features

### 🤖 AI Nutrition Assistant

- Nutrition-focused chatbot
- Context-aware dietary guidance
- Food and nutrition Q&A
- Personalized recommendations
- Conversational health support

---

### 🍽 Meal Planning System

- Personalized meal suggestions
- Daily nutrition planning
- Goal-based meal recommendations
- Balanced dietary guidance

---

### 🔥 Calorie Tracking

- Daily calorie monitoring
- Intake visualization
- Consumption logging
- Nutrition progress tracking

---

### 📊 Nutrition Dashboard

- Daily nutrition summaries
- Progress visualization
- Dietary trend monitoring
- User health insights

---

### 👤 User Management

- User authentication
- Registration & login
- Profile management
- Personalized user experience

---

### 📚 Nutrition Knowledge Base

- Structured food database
- Nutritional information retrieval
- Nutrition-focused knowledge support
- Retrieval-Augmented Generation (RAG)

---

### 💬 Chat History

- Conversation persistence
- Historical chat records
- Context-aware interactions
- User activity tracking

---

### 📄 Report Generation

- Nutrition summaries
- Export capabilities
- PDF generation support
- User progress reporting
## 🛠 Technology Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- Recharts
- Framer Motion

### Backend

- Flask
- Python

### Artificial Intelligence

- Gemini API
- Retrieval-Augmented Generation (RAG)
- Local LLM Support
- Qwen
- Ollama

### Database & Storage

- Firebase
- SQL Database Models

### Analytics

- Recharts
- Dashboard Visualization

### Development Tools

- Docker
- Git
- GitHub

## 🏗 System Architecture

NutriBot follows a multi-layer architecture consisting of:

### 1. Presentation Layer

Responsible for user interaction.

Components:

- Dashboard
- Meal Planner
- Chat Interface
- Profile Management

---

### 2. Application Layer

Responsible for business logic.

Components:

- Authentication
- Calorie Tracking
- Meal Planning
- User Management

---

### 3. AI Layer

Responsible for intelligent services.

Components:

- Gemini Integration
- RAG Service
- Nutrition Chatbot
- Local LLM Support

---

### 4. Data Layer

Responsible for information storage.

Components:

- Nutrition Database
- User Records
- Chat History
- Dietary Tracking
## 📁 Project Structure

```bash
nutribot/
│
├── backend-flask/
│   ├── routes/
│   │   ├── auth.py
│   │   ├── chat.py
│   │   └── history.py
│   │
│   ├── services/
│   │   ├── food_database.py
│   │   ├── nutrition.py
│   │   ├── llm.py
│   │   ├── local_llm.py
│   │   └── rag_service.py
│   │
│   ├── models.py
│   ├── app.py
│   └── requirements.txt
│
├── nutribot-next/
│   ├── src/
│   │   ├── app/
│   │   │   ├── dashboard/
│   │   │   ├── login/
│   │   │   ├── register/
│   │   │   └── profile/
│   │   │
│   │   ├── components/
│   │   ├── hooks/
│   │   └── lib/
│   │
│   ├── public/
│   └── package.json
│
├── docker-compose.yml
└── README.md
```
## 👥 Team Contributions

This project was developed collaboratively as part of an undergraduate Artificial Intelligence and Software Engineering project.

Areas of contribution included:

- Frontend Development
- Backend Development
- AI Integration
- Nutrition Database Development
- User Experience Design
- Testing & Validation

My primary contribution focused on:

- Frontend Development
- Dashboard Interface Implementation
- User Interaction Workflows
- Nutrition Tracking Features
- Chatbot Interface Integration

## 📈 Future Improvements

- Mobile Application Support
- Wearable Device Integration
- Personalized Nutrition Analytics
- AI-Based Food Recognition
- Barcode Scanning
- Real-Time Health Monitoring
- Multi-Language Support
- Advanced Recommendation Engine
