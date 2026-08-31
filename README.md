

# Kegel Muscle Exerciser

A minimalist, offline-first Android app for practicing Kegel muscle exercises, with configurable series, animated timers, and session tracking — all running locally on your device, no internet required.

## ✨ Features

- Create and save multiple exercise series with custom settings
- Configure contraction time, relaxation time, and number of repetitions independently per series
- Animated progress bar for each phase (contraction and relaxation)
- Full session progress bar showing how far along you are
- Large countdown timer so you can follow along without squinting
- Pause and resume the session at any time
- Mark one series as active and jump straight to it
- Delete series you no longer need
- All data saved locally on the device — works 100% offline
- Clean dark interface optimized for mobile screens

## 📖 How to use

### Creating a series

1. Open the Settings tab
2. Adjust the sliders for Clench time, Relax time, and Repetitions
3. Type a name for the series in the Save as field
4. Tap Save — the series appears in the list below

### Starting an exercise session

1. Tap any series in the list to select it
2. Switch to the Exercise tab — you will see the series name and its settings
3. Tap START to begin
4. Follow the on-screen cues: green means clench, red means relax
5. The countdown timer and progress bars update in real time

### Pausing and resuming

Tap the Pause button at any time during a session. Tap Resume to continue from where you left off. The timer picks up exactly where it stopped.

### Managing series

- Tap a series to select it and load it into the Exercise tab
- Tap the ✕ button on any series to delete it
- The active series is highlighted and marked with an "active" badge

## 🏗️ Interface

The app has two tabs at the top:

Settings — where you create and manage your exercise series.

Exercise — where you run your sessions. It shows a ready screen with the selected series details, then switches to the running view when you tap START.

The running view contains:

- A Pause / Resume button at the top
- A session progress bar showing overall completion
- A phase label telling you whether to clench or relax
- A phase progress bar for the current contraction or relaxation
- A large countdown timer
- A rep counter showing your current repetition out of the total

## 💾 Data and persistence

All series are saved automatically in the browser's localStorage every time you create, select, or delete a series. Your data persists between sessions and survives closing the app. No account, no cloud, no internet connection needed.

## 🛠️ Technology

Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step required. Runs entirely on-device via a WebView wrapper.

## 📄 License

MIT — feel free to use, modify, and distribute.

## 🙌 Author

Made by resina37451. Feedback and contributions are welcome!

---

É só copiar e colar no GitHub. Quer ajustar alguma coisa?
