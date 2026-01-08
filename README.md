# 🌍 GeoPulse: Global Etiquette AI Guide

**GeoPulse** is an interactive, cultural companion designed to help travelers and professionals master global etiquette. With a premium, modern interface, it provides instant access to cultural norms, do's and don'ts, and dining etiquette for countries worldwide.

## ✨ Features

- **Interactive Explorer**: Search for any country to instantly view a curated "Cultural Snapshot" covering Greetings, Dining, and Taboos.
- **"Test Your Knowledge" Quiz**: A gamified experience with progress tracking and immediate feedback to test your cultural IQ.
- **Geo Assistant**: A smart, contextual chatbot that answers specific questions like *"Can I tip in Japan?"* or *"What is the dress code in Brazil?"*.
- **Premium UI**: A fully responsive, glassmorphism-inspired design featuring smooth animations, "blob" backgrounds, and dark-mode aesthetics for the quiz.

## 🛠️ Tech Stack

### Frontend
- **React.js**: Modular component architecture (`HomePage`, `QuizPage`, `ChatWidget`).
- **React Router**: Seamless client-side navigation.
- **Lucide React**: Beautiful, consistent iconography.
- **Vanilla CSS**: Custom "GeoPulse" Design System (Semantic variables, Glassmorphism, Animations) without external framework bloat.

### Backend
- **FastAPI**: High-performance Python web framework for the API.
- **SQLAlchemy**: ORM for managing the SQLite cultural database.
- **Pydantic**: Robust data validation.

## 🚀 Getting Started

### Prerequisites
- Node.js & npm
- Python 3.9+

### Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/Yeshwanth2124/Geopluse.git
    cd Geopluse
    ```

2.  **Backend Setup**
    ```bash
    cd Backend
    python -m venv venv
    # Windows:
    .\venv\Scripts\activate
    # Mac/Linux:
    # source venv/bin/activate
    
    pip install -r requirements.txt
    
    # Seed the database
    python -m app.seeds
    
    # Run the server
    uvicorn app.main:app --reload
    ```

3.  **Frontend Setup**
    ```bash
    cd Frontend/cultural-guide-frontend
    npm install
    npm start
    ```

4.  **Explore**: Open [http://localhost:3000](http://localhost:3000) to start your journey!

## 📂 Project Structure

```
GeoPulse/
├── Backend/              # FastAPI Application
│   ├── app/
│   │   ├── main.py       # API Entry point
│   │   ├── models.py     # Database Schema
│   │   ├── chat_service.py # Chat Logic
│   │   └── ...
│   └── data.json         # Cultural Knowledge Base
│
└── Frontend/             # React Application
    └── cultural-guide-frontend/
        ├── src/
        │   ├── components/ # Header, ChatWidget
        │   ├── pages/      # HomePage, QuizPage
        │   ├── App.css     # Premium Styling
        │   └── ...
```
## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## Author

**Yeshwanth Goud**

*Data Scientist | Full Stack & ML Enthusiast*

