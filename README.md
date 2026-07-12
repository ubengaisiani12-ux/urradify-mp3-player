# URRADIFY - Desktop MP3 Player Application

URRADIFY is an offline GUI-based MP3 player application built with Python and PyQt6 Designer, developed as a Final Project for the Programming course. The application features an integrated user authentication system and a stacked layout system for elegant multi-page navigation.

## ✨ Features
- **User Authentication**: Secure and interactive Login Page gateway before accessing the music dashboard.
- **Offline Playback**: Plays local MP3 files stored directly within the project directory.
- **Multi-Page Navigation**: Implements `QStackedWidget` for a seamless transition from Login to Dashboard.
- **Modern UI Layout**: A clean, dark-themed desktop interface completely designed using PyQt6 Qt Designer.
- **Audio Control**: Interactive controllers featuring Play, Pause, Stop, and volume sliders.

## 📁 Project Structure
- `assets/` : Stores images, icons, and album art for the songs.
- `music/`  : Dedicated directory for local MP3 audio files.
- `models/` : Contains the backend logic, authentication handlers, and data structures.
- `ui/`     : Holds the `.ui` layout files generated from Qt Designer.

## 🚀 My Role (Lead Developer)
- Designed the core desktop layout, authentication forms, and dark-mode UI aesthetics.
- Developed the Python backend logic, multi-page page routers (`QStackedWidget`), and user login validation.
- Handled modular directory storage management for offline MP3 files and graphical assets.
- Utilized AI tools to implement rapid debugging and audio thread optimization.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **GUI Framework:** PyQt6 & Qt Designer
- **Audio System:** PyQt6.QtMultimedia / Pygame

## 💻 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Navigate to the project directory:
   ```bash
   cd urradify-mp3-player
   ```
3. Install the required libraries:
   ```bash
   pip install PyQt6
   ```
4. Run the application:
   ```bash
   python main.py
   ```
