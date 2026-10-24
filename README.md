# 🚀 CareerLens AI — AI-Powered Career Guidance

**Discover your potential. Analyze your skills. Build your future.**

CareerLens AI is an AI-powered career guidance web application designed to help students and job seekers understand their skills, identify skill gaps, explore suitable career paths, and create a roadmap for their professional growth.

The application analyzes resume information and provides personalized career recommendations, learning roadmaps, project suggestions, and resume improvement tips.

## ✨ Features

* 📄 **Resume Analysis** — Analyze resume content to understand your skills and experience.
* 🎯 **Career Recommendations** — Explore career paths based on your profile, skills, and interests.
* 🧠 **Skill Gap Analysis** — Identify skills you may need to develop for your target career.
* 🗺️ **Personalized Learning Roadmap** — Get guidance on what to learn next.
* 💡 **Project Suggestions** — Discover project ideas to strengthen your portfolio.
* 📝 **Resume Improvement Tips** — Find ways to improve your resume.
* 💼 **Career Exploration** — Explore careers such as AI Engineer, Data Analyst, Machine Learning Engineer, and Python Developer.
* 🌐 **Web-Based Interface** — Access the application through your web browser.

## 🛠️ Tech Stack

| Technology       | Purpose                                                 |
| ---------------- | ------------------------------------------------------- |
| Python           | Backend programming                                     |
| Flask            | Web application framework                               |
| HTML5            | Webpage structure                                       |
| CSS3             | Styling and responsive design                           |
| JavaScript       | Frontend interactivity                                  |
| Google GenAI SDK | AI integration                                          |
| Gemini API       | AI-powered analysis, using a configured supported model |
| Git & GitHub     | Version control and project hosting                     |

## 📁 Project Structure

```text
CareerLens_AI/
│
├── app.py
├── ai_service.py
├── career_data.py
├── requirements.txt
├── .env
├── .env.example
├── .gitignore
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    ├── css/
    │   └── style.css
    │
    ├── js/
    │   └── main.js
    │
    └── images/
```

### 📌 Main Files

* `app.py` — Runs the Flask application and handles API routes.
* `ai_service.py` — Handles AI-powered resume analysis.
* `career_data.py` — Stores career information and recommendations.
* `templates/index.html` — Contains the website's HTML structure.
* `static/css/style.css` — Defines the website's appearance.
* `static/js/main.js` — Handles frontend interactions and API requests.
* `requirements.txt` — Lists the Python dependencies.
* `.env` — Stores local environment variables, including the API key.
* `.env.example` — Provides an example of the required environment variables.

## ⚙️ Installation and Setup

Follow these steps to run CareerLens AI on your computer.

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Open the Project Folder

```bash
cd CareerLens_AI
```

Open this folder in Visual Studio Code.

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Environment Variables

Create or update your `.env` file in the project root:

```env
GEMINI_API_KEY=your_actual_api_key
GEMINI_MODEL=gemma-3-27b-it
```

Replace `your_actual_api_key` with your valid API key. Ensure that the configured model is available to your API key.

**Security note:** Never upload your real API key to GitHub. Keep `.env` in `.gitignore` and use `.env.example` only as a template.

### 6. Run the Application

```bash
python app.py
```

When the Flask server starts successfully, open this address in your browser:

```text
http://127.0.0.1:5000
```

The application runs locally on your computer.

## 🔍 How It Works

1. Open the CareerLens AI website.
2. Enter your resume information.
3. Add your skills and career interests.
4. Submit the information for analysis.
5. Review the available AI-generated career guidance.
6. Use the suggested skills, roadmap, and projects to plan your learning.

AI-generated recommendations should be reviewed carefully and treated as guidance rather than guaranteed career outcomes.

## 🎯 Target Users

* College students exploring career options.
* Freshers preparing for placements.
* Job seekers improving their resumes.
* Beginners learning programming and AI.
* Students planning their technical skill development.

## 🔮 Future Enhancements

Potential future improvements include:

* Resume file upload and parsing.
* Resume scoring and detailed feedback.
* Job description and resume matching.
* Skill-based career matching.
* Learning resource recommendations.
* User accounts and saved analysis reports.
* Career progress tracking.
* Deployment to a public hosting platform.

These are planned enhancements and may not be available in the current version.

## 🔐 Privacy and Security

* Do not submit sensitive personal information unnecessarily.
* Keep API keys and other secrets out of public repositories.
* Review AI-generated results before relying on them.
* Configure secure storage and privacy controls before deploying the application for public use.

## 👩‍💻 Developer

**Lahari Vissamessty**

B.Sc. Artificial Intelligence & Robotics Student

Interested in Artificial Intelligence, Python, and building practical AI-powered applications.

## 📜 License

A license has not yet been specified for this project. Add a `LICENSE` file if you intend to distribute the project under a particular open-source license.

---

⭐ **CareerLens AI — Turn your skills into career possibilities.**
