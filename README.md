# 🎯 ScreenShooter

ScreenShooter is a lightweight, cross-platform GUI tool that lets you define a custom capture region, assign a global hotkey, and automatically save screenshots to your chosen folder. Perfect for quickly grabbing snippets of your screen without having to open bulky screenshot utilities.

---

## 🚀 Features

- **Region Selection**  
  Draw a rectangular capture area on your screen once, and reuse it for all future screenshots.

- **Custom Hotkey**  
  Assign any key combination (e.g. `Ctrl+Shift+S`) to trigger the capture instantly—no more fumbling through menus.

- **Auto-Save to Folder**  
  Choose your destination folder once; all subsequent screenshots are saved there automatically, with timestamped filenames.

- **Cross-Platform**  
  Works on Windows, macOS, and Linux (X11) with the same codebase.

- **Lightweight & Fast**  
  Minimal dependencies and instant response time.

---

## 🛠️ Technologies Used

- **Python 3.7+**  
- **PyQt5** (or **Tkinter**) for the GUI  
- **PyAutoGUI** for screen capture  
- **keyboard** (Windows/Linux) / **pynput** (macOS) for global hotkeys  
- **OS** / **pathlib** for file management  

---

## 📦 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/screenshooter.git
   cd screenshooter
