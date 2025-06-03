# 🎥 Video Catcher Web App

**Video Catcher** is a simple Flask-based web application that allows users to download YouTube videos in the best available quality. It uses `yt-dlp` under the hood and is designed to be deployed easily on platforms like Render or PythonAnywhere.

---

## 🌐 Live Demo

Want to see it in action? Visit: [www.urdujahaan.com](http://www.urdujahaan.com)

---

## 📦 Features

- 🖱️ Easy to use: Just paste a YouTube URL and click download.
- 🎞️ Downloads the best video + audio format by default.
- 📁 Automatic download and delivery of the video file.
- 🔒 Environment-based config and secret support with `.env`.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/video-catcher-web.git
cd video-catcher-web
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Create a `.env` File

```env
# .env
SECRET_KEY=your-secret-key
YDL_OUTPUT_DIR=downloads
```

### 5. Run the App Locally

```bash
python app.py
```

Go to `http://127.0.0.1:5000` in your browser.

---

## ☁️ Deployment (Render Recommended)

1. Push this code to GitHub.
2. Go to [https://render.com](https://render.com).
3. Create a new Web Service:
   - Runtime: Python 3.x
   - Start command: `python app.py`
4. Add environment variables:
   - `SECRET_KEY=your-secret-key`
   - `YDL_OUTPUT_DIR=downloads`
5. Done! Your app will now be live and working.

---

## 📂 Project Structure

```
video_catcher_web_env/
├── app.py
├── .gitignore
├── requirements.txt
├── templates/
│   └── index.html
└── .env  (not included in repo, add manually)
```

---

## 🔧 Technologies Used

- Flask
- yt-dlp
- python-dotenv
- HTML/CSS (basic)

---

## 📞 Contact

- Maintainer: [@yaseenhasbi](https://github.com/yaseenhasbi)
- Website: [www.urdujahaan.com](http://www.urdujahaan.com)
- Email: yaseenhasbi@gmail.com

---

## 📄 License

This project is open-source and free to use. Attribution is appreciated. 😊