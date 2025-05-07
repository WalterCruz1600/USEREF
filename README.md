# React Stopwatch with Hooks

A simple, dependency-free stopwatch built with React Hooks: `useState`, `useEffect`, and `useRef`. No npm or bundler required—just open the HTML file in your browser to get started.

## 📋 Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Built With](#built-with)

## 🚀 Features

- **Start/Pause**: Toggle the stopwatch on and off.
- **Reset**: Clear the timer back to `00:00:00`.
- **Lap Saving**: Record multiple time sessions and display a scrollable list.
- **Optimized Timer**: Uses `useRef` to store the interval ID and `useEffect` for setup/cleanup, preventing stale timers.
- **Modern UI**: Clean, responsive design with CSS transitions and Google Fonts.
- **No Build Tools**: Delivered as a single `index.html` file with CDN-hosted React, ReactDOM, and Babel.

## 🛠️ Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/WalterCruz1600/USERREF.git
   cd USERREF
   ```
2. **Open in Browser**
   - Double-click `index.html`, or open it in your favorite browser.

## 📖 Usage

1. **Start/Pause**: Click **Iniciar** to start counting; click **Pausar** to pause.
2. **Reset**: Click **Reiniciar** to reset the timer to zero.
3. **Save Lap**: When the timer is running or paused, click **Guardar** to record the current time into the session list.
4. **View Sessions**: Scroll through the recorded sessions below the controls.

## 🗂️ File Structure

```plaintext
USERREF/
├── index.html    # Main stopwatch code and styles
└── README.md     # This file
```

## 🛠️ Built With

- **React** via CDN – Component-based UI library
- **Babel Standalone** – JSX transformation in the browser
- **React Hooks** (`useState`, `useEffect`, `useRef`) – State, side-effects, and mutable refs
- **CSS** – Styling and layout



