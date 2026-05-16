# 💕 Good Morning — A Love Letter Website

A beautiful, animated good morning website built with Flask — because some feelings deserve more than a text message.

---

## ✨ Features

- 🌅 **Animated Intro Screen** — A cinematic opening to set the mood
- 💌 **Love Messages Section** — Sweet messages that scroll and reveal
- 🖼️ **Gallery Section** — A photo gallery to showcase your memories
- 📬 **Open When Section** — "Open when..." letters for different moments
- 💛 **Reasons Section** — A list of reasons, just for them
- 🔮 **Secret Easter Egg** — A hidden surprise waiting to be discovered
- 🎬 **Smooth Animations** — Scroll-reveal effects throughout
- 📱 **Fully Responsive** — Looks great on mobile and desktop

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/good-morning-for-your-gf-lol.git
   cd good-morning-for-your-gf-lol
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**
   ```bash
   python app.py
   ```

5. **Open in browser**
   ```
   http://localhost:5000
   ```

---

## 🌐 Deploying to GitHub Pages / Render / Railway

This is a Flask app, so it needs a Python server. Easy free options:

- **[Render](https://render.com)** — Connect your GitHub repo, set start command to `gunicorn app:app`
- **[Railway](https://railway.app)** — One-click deploy from GitHub
- **[PythonAnywhere](https://www.pythonanywhere.com)** — Free Flask hosting

---

## 🗂️ Project Structure

```
good-morning-for-your-gf-lol/
├── app.py                  # Flask app entry point
├── requirements.txt        # Python dependencies
├── .gitignore
├── README.md
├── static/
│   ├── css/
│   │   └── style.css       # All the styling
│   └── js/
│       └── main.js         # Animations & interactions
└── templates/
    └── index.html          # Main page (all sections live here)
```

---

## 🛠️ Customization

Want to make it yours? Here's what to edit:

| What | Where |
|------|-------|
| Messages & text | `templates/index.html` |
| Colors & fonts | `static/css/style.css` |
| Animations | `static/js/main.js` |
| Photos | Add images to `static/` and reference in HTML |

---

## 📦 Dependencies

| Package | Purpose |
|---------|---------|
| Flask | Web framework |
| Gunicorn | Production server |
| google-auth | Auth support |

---

## 📄 License

This project is open source and free to use. Make someone smile. 💛

---

> *Made with love. For someone special.*
