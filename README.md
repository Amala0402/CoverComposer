# 🎵 CoverComposer – Generative AI Music Generation Platform

🔍 Generate, Play, Download, and Manage Music with AI

CoverComposer is a FastAPI-based web application that generates instrumental music based on user preferences such as Mood, Genre, Tempo, and Style. The platform combines Generative AI techniques with MIDI music synthesis to create unique audio tracks and provide an interactive music experience.

---

## 🚀 Project Overview

This project generates AI-powered instrumental music and provides:

✅ User Registration & Login Authentication
✅ AI Music Generation using Markov Chains
✅ Mood-Based Melody Generation
✅ Genre-Based Instrument Selection
✅ MIDI to WAV Audio Conversion
✅ MP3 Music Library
✅ Recent Songs History
✅ Liked Songs Management
✅ Download Generated Music
✅ Dark-Themed Responsive User Interface

---

## 🧠 Tech Stack & Tools Used

| Category             | Technologies / Libraries       |
| -------------------- | ------------------------------ |
| Programming Language | Python                         |
| Framework            | FastAPI                        |
| Database             | SQLite + SQLAlchemy ORM        |
| Frontend             | HTML, CSS, Jinja2 Templates    |
| Authentication       | SessionMiddleware              |
| Music Generation     | MIDIUtil                       |
| Audio Rendering      | FluidSynth + SoundFont         |
| AI Algorithm         | Markov Chain Melody Generation |
| Server               | Uvicorn                        |

---

## 📂 Folder Structure

```text
covercomposer/
│
├── static/
│   ├── style.css
│   ├── songs/
│   └── output/
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   ├── index.html
│   ├── result.html
│   ├── mp3songs.html
│   ├── mp3_result.html
│   ├── liked.html
│   ├── recent.html
│   ├── profile.html
│   └── settings.html
│
├── database.py
├── models.py
├── main.py
├── requirements.txt
├── soundfont.sf2
└── README.md
```

---

## 🧩 Features Explanation

### 1️⃣ User Authentication

Users can create accounts and securely log in to access application features.

### 2️⃣ Dashboard

Provides quick navigation to:

* Generate Music
* MP3 Library
* Recent Songs
* Liked Songs
* Settings

### 3️⃣ AI Music Generation

Users select:

* Mood
* Genre
* Tempo
* Style

The system generates melodies using a Markov Chain algorithm and creates audio tracks dynamically.

### 4️⃣ MIDI Generation

MIDIUtil is used to:

* Create melodies
* Add bass layers
* Add drum patterns
* Configure instruments based on genre

### 5️⃣ Audio Rendering

Generated MIDI files are converted into WAV audio files using FluidSynth and SoundFont technology.

### 6️⃣ MP3 Music Library

Users can browse and play predefined MP3 songs based on selected preferences.

### 7️⃣ Recent Songs

Displays recently generated or played songs for quick access.

### 8️⃣ Liked Songs

Users can:

* Save favorite songs
* Replay liked tracks
* Download songs
* Remove songs from favorites

### 9️⃣ Settings & Profile

Users can:

* View profile information
* Manage account settings
* Logout securely

---

## ⚙️ Setup Instructions (Run Locally)

### 🪜 Step 1: Clone Repository

```bash
git clone https://github.com/Amala0402/covercomposer.git
cd covercomposer
```

### 🪜 Step 2: Create Virtual Environment

```bash
python -m venv venv
```

### 🪜 Step 3: Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux / Mac:

```bash
source venv/bin/activate
```

### 🪜 Step 4: Install Requirements

```bash
pip install -r requirements.txt
```

### 🪜 Step 5: Run Application

```bash
uvicorn main:app --reload
```

### 🪜 Step 6: Open Browser

Visit:

```text
http://127.0.0.1:8000
```

---

## 🎼 Music Generation Workflow

Step 1:
User logs into the application.

Step 2:
User selects Mood, Genre, Tempo, and Style.

Step 3:
Markov Chain algorithm generates musical notes.

Step 4:
MIDIUtil creates a MIDI composition.

Step 5:
FluidSynth converts MIDI into WAV audio.

Step 6:
Generated music is played inside the application.

Step 7:
Users can download or like songs.

Step 8:
Songs are stored in Recent Songs and Liked Songs sections.

---

## 🧑‍💻 Author

👩‍💻 Amala Kanaparthi

Fourth-Year Engineering Student | Passionate about Artificial Intelligence, Music Technology, and Full Stack Development

📧 Email: [kanaparthiamala226@gmail.com](mailto:kanaparthiamala226@gmail.com)

🌐 GitHub: https://github.com/Amala0402

---

## 🏁 Conclusion

CoverComposer is a complete AI-powered music generation platform that combines FastAPI, Generative AI, MIDI synthesis, and audio rendering technologies to create unique music tracks based on user preferences. The project demonstrates how artificial intelligence can be applied to automated music composition through an interactive and user-friendly web application.

⭐ If you like this project, please give it a star on GitHub!
