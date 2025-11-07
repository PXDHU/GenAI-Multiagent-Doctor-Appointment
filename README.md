# Multiagent Doctor Appointment System 🏥

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115.8-009688.svg)](https://fastapi.tiangolo.com)
[![Streamlit](https://img.shields.io/badge/Streamlit-latest-FF4B4B.svg)](https://streamlit.io)
[![LangChain](https://img.shields.io/badge/LangChain-0.3.18-00873E.svg)](https://python.langchain.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A sophisticated multi-agent system for intelligent doctor appointment scheduling powered by LangChain and Large Language Models.

## 🌟 Features

- 🤖 Multi-agent architecture for intelligent appointment scheduling
- 📅 Smart availability management for doctors
- 🎯 Context-aware scheduling based on patient requirements
- 💻 Streamlit-based user interface for easy interaction
- 🔄 Real-time availability updates
- 📊 Data-driven decision making
- 🔒 Secure and scalable architecture

## 🛠️ Technology Stack

- **Backend Framework:** FastAPI
- **Frontend:** Streamlit
- **AI/ML:** LangChain, Google Generative AI
- **Database:** SQLAlchemy, Peewee
- **Data Processing:** Pandas, NumPy
- **Authentication:** JWT, bcrypt
- **Documentation:** FastAPI Swagger/OpenAPI

## 📋 Prerequisites

- Python 3.10 or higher
- Virtual environment (recommended)
- Required API keys for LLM services

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/PXDHU/Multiagent-Doctor-Appointment.git
   cd Multiagent-Doctor-Appointment
   ```

2. **Set up virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # OR
   .\venv310\Scripts\activate  # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -e .
   ```

4. **Configure environment variables**
   ```bash
   # Create .env file with required configurations
   touch .env
   ```

5. **Run the application**
   ```bash
   # Start the FastAPI backend
   uvicorn main:app --reload

   # Start the Streamlit UI (in a new terminal)
   streamlit run streamlit_ui.py
   ```

## 📁 Project Structure

```
Multiagent-Doctor-Appointment/
├── agent.py                    # Agent definitions and logic
├── main.py                    # FastAPI application entry point
├── streamlit_ui.py            # Streamlit UI implementation
├── data/
│   └── doctor_availability.csv # Doctor availability data
├── data_models/
│   └── models.py              # Database models
├── prompt_library/
│   └── prompt.py              # LLM prompts
├── toolkit/
│   └── toolkits.py            # Agent tools and utilities
├── utils/
│   └── llms.py               # LLM configurations
└── notebook/
    └── multiagent_system.ipynb # Development notebook
```

## 🔧 Configuration

1. Create a `.env` file in the root directory
2. Add the following configurations:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   GROQ_API_KEY=your_google_api_key
   ```

## 📚 API Documentation

Once running, access the API documentation at:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`


## 📈 Performance

- Handles multiple concurrent appointment requests
- Real-time availability updates
- Efficient conflict resolution
- Scalable architecture

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request


## 👨‍💻 Author

**Padmavasan Balakrishnan**
- Email: padmavasan.contact@gmail.com
- GitHub: [@PXDHU](https://github.com/PXDHU)

---
⭐️ Star this repository if you find it helpful!