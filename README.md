Aesthetic Pomodoro Timer

A beautifully designed Pomodoro Timer built with HTML, TailwindCSS, and JavaScript.
This app helps you boost productivity by following the Pomodoro Technique (25 minutes of focus + 5 minutes break).

It comes with:
✅ Dark/Light mode toggle
✅ Customizable focus & break times
✅ Session tracking
✅ Music playback with a real-time audio visualizer
✅ Aesthetic glassmorphism UI

📸 Preview

(Add screenshots or GIFs of your app here)

🚀 Features
🎨 Aesthetic Design

Glassmorphism-inspired card layout

Smooth animations and transitions

Responsive design for desktop & mobile

⏳ Timer Functionality

Adjustable Pomodoro time (1–60 minutes)

Adjustable Break time (1–30 minutes)

Start / Pause / Reset controls

Automatic switch between focus & break sessions

🎵 Music Player with Visualizer

Upload your own audio file (MP3, WAV, etc.)

Plays music while you work

Animated bar visualizer that reacts to sound

🌙 Dark Mode

Toggle between Light and Dark mode

Adaptive colors and icons (sun 🌞 / moon 🌙)

🔔 Custom Notifications

Popup message box when:

A Pomodoro ends ("Time for a break!")

A Break ends ("Back to focus!")

📊 Session Tracking

Keeps count of how many Pomodoro sessions you’ve completed

🛠️ Technologies Used

HTML5 – Structure

CSS3 / TailwindCSS – Styling & responsiveness

JavaScript (Vanilla) – Timer, audio, visualizer, dark mode

Canvas API – Audio frequency visualization

📂 Project Structure
.
├── index.html        # Main app (single page)
├── README.md         # Documentation (this file)
└── assets/           # (Optional) place for screenshots, icons, etc.

⚡ Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/aesthetic-pomodoro-timer.git
cd aesthetic-pomodoro-timer

2️⃣ Open in Browser

Since it’s a static project, you don’t need any build tools. Just open index.html in your favorite browser:

open index.html   # MacOS
start index.html  # Windows
xdg-open index.html  # Linux


Or use VS Code Live Server for auto-refresh:

npm install -g live-server
live-server

⚙️ Usage

Set your desired Pomodoro time and Break time in minutes.

Click Start to begin.

Work until the timer ends → A notification will pop up.

Take your break → A new notification signals when it’s over.

Upload music if you want to study/work with visual beats 🎶.

Track your sessions count on the UI.

🖤 Dark Mode

Click the sun/moon icon (top right) to toggle between light and dark themes.

The app remembers your preference for the session.

🎵 Music Visualizer

Upload an audio file (.mp3, .wav, etc.).

The Canvas API generates animated bars that move with the beat.

Works best with high-bass tracks for a cool effect.


🔮 Future Improvements

 Add long breaks after 4 sessions

 Save session history in localStorage

 Add sound alerts (ding/bell)

 Option to choose from preset themes

 PWA support (Installable app)

🤝 Contributing

Pull requests are welcome! Here’s how you can contribute:

Fork the repository

Create a new branch (git checkout -b feature-name)

Commit your changes (git commit -m "Added new feature")

Push the branch (git push origin feature-name)

Open a Pull Request 🎉

📜 License

This project is licensed under the MIT License – free to use, modify, and distribute.

💡 Inspiration

This project was made to:

Practice JavaScript DOM manipulation

Learn Canvas API for audio visualization

Create a minimal but aesthetic productivity tool
