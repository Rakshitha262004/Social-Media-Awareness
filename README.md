# Social-Media-Awareness
A web-based platform designed to educate users about safe and responsible social media usage. The project focuses on raising awareness about privacy risks, cyberbullying, phishing attempts, and online reputation management. It provides interactive modules, quizzes, and real-time alerts to help users make informed decisions .

---

## Technologies Used
- Python
- Pandas & NumPy for data handling
- JSON for post/profile data
- Flask / FastAPI for web interface
- HTML, CSS, JavaScript for frontend

---

## Features
- Analyze social media posts and profiles for risk
- Assign risk scores to posts and users
- Interactive dashboard for visualization
- JSON-based data ingestion for scalability
- Helps raise awareness on online safety and digital hygiene

---

## Folder / File Structure
Social_Media_Awareness/
│
├── app.py # Main web application
├── risk_engine.py # Core logic to calculate risk
├── data/ # JSON data of posts and profiles
├── frontend/ # HTML/CSS/JS files for dashboard
├── screenshots/ # Dashboard and engine screenshots
│ ├── app.png
│ ├── dashboard.png
│ ├── index.png
│ ├── posts_json.png
│ ├── profile_json.png
│ └── risk_engine.png
└── README.md # This file


---

## Screenshots
- `screenshots/app.png` – Main web app interface  
- `screenshots/dashboard.png` – Interactive dashboard view  
- `screenshots/index.png` – Home page layout  
- `screenshots/posts_json.png` – Sample posts JSON data  
- `screenshots/profile_json.png` – Sample profile JSON data  
- `screenshots/risk_engine.png` – Risk calculation engine output  

---

## How to Run / Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Social_Media_Awareness.git
cd Social_Media_Awareness
Install dependencies:
pip install -r requirements.txt
Run the application:
python app.py
Open your browser at http://localhost:8000
Upload or load JSON data to visualize social media risks in the dashboard
