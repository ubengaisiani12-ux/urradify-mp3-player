# URRADIFY - Desktop MP3 Player Application

URRADIFY is an offline GUI-based MP3 player application built with Python and PyQt6 Designer, developed as a Final Project for the Programming course.

## ✨ Features
- **Offline Playback**: Plays local MP3 files stored directly within the project's music directory.
- **Modern UI Layout**: A clean, dark-themed desktop interface completely designed using PyQt6 Qt Designer.
- **Audio Control**: Interactive controllers featuring Play, Pause, Stop, and integrated volume sliders.

## 📁 Project Structure
- `URRADIFY_UAS_FINAL/` : Main application folder containing the program files.
  - `assets/` : Stores interface graphics, application icons, and song cover albums.
  - `music/`  : Contains 1 sample local MP3 audio file for initial testing.
  - `models/` : Contains the core backend logic, functions, and data structures.
  - `ui/`     : Holds the `.ui` layout files generated from Qt Designer.
  - `main.py` : The main execution file of the application.
- `README.md` : Project documentation (this file).

## 📥 How to Get All Music Files (Google Drive)
To save space on GitHub, this repository only includes 1 sample song. If you want to listen to the full playlist:
1. Open and download the full music folder from this https://drive.google.com/drive/folders/1VL1aO9enmvVBoBfA5u-LfCb7JI_lwOcq?usp=sharing
2. Extract or copy all the downloaded `.mp3` files.
3. Paste/put them inside the `URRADIFY_UAS_FINAL/music/` folder on your local computer.

## 🚀 My Role (Lead Developer & Architect)
- Designed the core desktop layout, authentication forms, and dark-mode UI aesthetics.
- Developed the Python backend logic, page routers, and integrated the `.ui` files.
- Managed modular directory storage for offline MP3 files and graphical assets.
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
   cd urradify-mp3-player.
   ```
3. Enter the main application folder:
   ```bash
   cd URRADIFY_UAS_FINAL
   ```
4. Install PyQt6:
   ```bash
   pip install PyQt6
   ```
5. Run the application:
   ```bash
   python main.py
   ```
