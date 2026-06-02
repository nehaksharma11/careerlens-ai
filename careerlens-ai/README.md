# 🔍 CareerLens AI — Resume Analyzer & Career Recommendation System

<div align="center">

![CareerLens AI](https://img.shields.io/badge/CareerLens-AI-0EA5E9?style=for-the-badge&logo=artificial-intelligence)
![Free](https://img.shields.io/badge/100%25-FREE-10B981?style=for-the-badge)
![No API](https://img.shields.io/badge/No%20API-Required-8B5CF6?style=for-the-badge)
![Offline](https://img.shields.io/badge/Works-Offline-F59E0B?style=for-the-badge)

**An AI-Based Resume Analyzer and Career Recommendation System**  
*6th Semester Project · Computer Science Engineering · Dronacharya College of Engineering*

</div>

---

## 👩‍💻 Developed By

| Name | Enrollment No. |
|------|----------------|
| Pritidarshini Biswal | 26141 |
| Neha Kumari | 26906 |

**Batch:** 2023 – 2027 · **Department:** CSE · **Semester:** 6th

---

## 🌟 Live Demo

> Simply open `index.html` in any browser — no server, no install, no internet needed!

---

## 📌 About The Project

**CareerLens AI** is a fully client-side, browser-based resume analyzer that uses rule-based NLP and a skill-matching engine to provide intelligent resume analysis and career recommendations — entirely for free, with no API key or internet connection required.

In today's competitive job market, many candidates miss opportunities due to poorly structured resumes and limited awareness. Traditional ATS systems rely heavily on keyword matching. CareerLens AI bridges this gap by providing instant, actionable feedback.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📄 **Resume Parsing** | Upload `.txt`/`.pdf` or paste text directly |
| ⚡ **Skill Extraction** | Detects 500+ technical & soft skills from resume |
| 📊 **ATS Score** | Animated score ring with detailed breakdown |
| 🎯 **Job Role Prediction** | Matches against 10 career profiles with % match |
| 🔍 **Skill Gap Analysis** | Shows strong, partial & missing skills |
| 📚 **Course Recommendations** | Suggests free courses (Coursera, freeCodeCamp, etc.) |
| 💡 **Personalized Feedback** | 6 specific, actionable improvement tips |
| 📈 **Section Score Bars** | Individual scores for each resume section |

---

## 🛠️ Tech Stack

```
Frontend    →  HTML5, CSS3, Vanilla JavaScript
AI Engine   →  Rule-based NLP (local, browser-side)
Skills DB   →  500+ skills across 7 categories
Job Roles   →  10 career profile matchers
Animations  →  CSS Keyframes + Canvas API (particle BG)
Fonts       →  Google Fonts (Syne + Plus Jakarta Sans)
```

---

## 🚀 How To Run

### Option 1 — Direct (Easiest)
```bash
# Just open the file in your browser
double-click index.html
```

### Option 2 — Via Git Clone
```bash
git clone https://github.com/YOUR_USERNAME/careerlens-ai.git
cd careerlens-ai
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Option 3 — Live Server (VS Code)
1. Install the **Live Server** extension in VS Code
2. Right-click `index.html` → **Open with Live Server**

---

## 📂 Project Structure

```
careerlens-ai/
│
├── index.html          ← Main application (entire app in one file)
├── README.md           ← This file
├── LICENSE             ← MIT License
└── screenshots/        ← App screenshots
    ├── hero.png
    ├── results.png
    └── analysis.png
```

---

## 🧠 How The AI Engine Works

```
User Pastes Resume
        ↓
Text Preprocessing (lowercase, normalize)
        ↓
Section Detection  →  Contact / Education / Skills / Projects / Experience
        ↓
Skill Extraction   →  500+ skill patterns matched via smart includes()
        ↓
ATS Score Calc     →  Section score + Skill density + Format + Quantification
        ↓
Job Role Matching  →  10 role profiles × keyword overlap = match %
        ↓
Skill Gap Analysis →  Role keys present vs missing in resume
        ↓
Course Reco        →  Mapped to free platforms per missing skill
        ↓
Personalized Feedback → 6 rule-based tips based on detected patterns
```

---

## 🎯 Skills Database Coverage

| Category | Examples |
|----------|---------|
| **Languages** | Python, Java, JavaScript, C++, SQL, R, Go |
| **Frameworks** | React, Flask, Django, FastAPI, Spring, Vue |
| **ML / AI** | TensorFlow, PyTorch, scikit-learn, NLP, BERT |
| **Data** | Pandas, NumPy, Power BI, Tableau, Spark |
| **Cloud/DevOps** | AWS, Docker, Kubernetes, CI/CD, GitHub |
| **Other Tech** | Blockchain, IoT, Unity, Figma, Arduino |
| **Soft Skills** | Leadership, Agile, Scrum, Communication |

---

## 📸 Screenshots

> *(Add screenshots to the `/screenshots` folder and they'll appear here)*

---

## 🔮 Future Scope

- [ ] LinkedIn profile import
- [ ] AI chatbot integration (career counseling)
- [ ] Job portal API integration (Naukri, LinkedIn)
- [ ] Recruiter dashboard for candidate ranking
- [ ] Multi-language resume support
- [ ] Export analysis report as PDF

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

- **Dronacharya College of Engineering**, Department of CSE
- Coursera, freeCodeCamp, Google, HuggingFace for free course resources
- Inspired by the need for accessible career tools for students

---

<div align="center">
Made with ❤️ by <strong>Pritidarshini Biswal & Neha Kumari</strong><br/>
CSE · Dronacharya College of Engineering · Batch 2023–2027
</div>
