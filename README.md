# Jarvis-Like Voice Assistant

A voice-driven Python assistant powered by `pyttsx3`, SpeechRecognition, OpenCV, and more. It responds to natural speaking, allowing tasks like web search, camera capture, music playback, time checks, and setting reminders.

---

##  Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

-  Voice-based interaction (`pyttsx3` & `SpeechRecognition`)
-  Web search via Wikipedia and browser launch
-  Local music playback
-  Camera use for capturing images (`OpenCV`)
-  Time inquiry and reminder scheduling
-  Friendly greetings (Good morning/afternoon/evening)

---

## Tech Stack

- Python
- `pyttsx3` for TTS
- `SpeechRecognition` + `pyaudio` for ASR
- `OpenCV` for camera access
- `wikipedia`, `webbrowser`, `datetime`, `os`, `time`

---

## Getting Started

### Prerequisites

- Python 3.7+
- `pip` installed

### Installation

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
