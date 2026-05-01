# 🎵 PocketTrack

A lightweight offline song management & recommendation system built with **C++ and Object-Oriented Programming (OOP)**.

Designed for students and casual listeners who want a **simple, private, low-resource music manager** without relying on paid streaming services.

---

## 📸 Preview & Demo

### 🎧 Main Interface

This is the main interface of **PocketTrack**, where users can navigate through the system and access playlists, search, and recommendations.

<img width="1280" height="762" alt="Interface" src="https://github.com/user-attachments/assets/51e0679d-209c-4989-84cf-368441e6de85" />


---

### ▶️ Playing Mode

This view shows the playback system in action. Users can control songs using play, pause, next, and previous options (simulated in this version).

<img width="1280" height="761" alt="Songs Playing" src="https://github.com/user-attachments/assets/7f7cd67a-36e6-4dda-894b-24b22a15cc04" />

---

### 🔍 Search & Recommendation

Users can search songs by mood, genre, or keywords. The system provides smart recommendations based on input and listening history.

<img width="1280" height="762" alt="Interface" src="https://github.com/user-attachments/assets/f516756a-fa75-4205-9250-1485d77d3495" />


---

## ✨ Features

* 🎵 Manage local song library (CSV / folder scan)
* ▶️ Playback controls (Play / Pause / Next / Previous)
* 📂 Create, edit, and delete playlists
* ⭐ Rate songs (1–5) and mark favorites
* 📊 Track listening history
* 🤖 Smart recommendations based on:

  * Genre
  * Mood
  * Ratings
  * Play counts
* 🌐 Online + Offline mode support

---

## ⚙️ How It Works

### 🟢 Online Mode

* Search songs using mood, genre, or keywords
* Fetch recommended tracks (YouTube metadata or simulated)
* Save songs as “cloud suggestions”
* Rate and add to playlists

### 🔴 Offline Mode

* Load local metadata (CSV or saved files)
* Browse and play songs (simulated)
* Create and manage playlists
* Generate recommendations using:

  * Genre & mood tags
  * User ratings
  * Listening history

---

## 🏗️ System Architecture

Core classes used in the project:

* `Song` → stores song metadata
* `SongLibrary` → manages collection of songs
* `UserProfile` → tracks user activity and history
* `Playlist` → manages playlists
* `Player` → handles playback controls
* `Recommender` → generates song suggestions

---

## 🧪 Example Usage

**Input:**

```
Search: "sad calm songs"
```

**Output:**

```
🎧 Recommended:
- Song A
- Song B
- Song C
```

---

## 🛠️ Built With

* C++
* Object-Oriented Programming (OOP)
* File Handling (CSV / Text / Binary)
* (Optional) SFML / Qt for GUI

---

## ⚡ Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/pockettrack.git
cd pockettrack
```

### Compile

```bash
g++ main.cpp -o pockettrack
```

### Run

```bash
./pockettrack
```

---

## 🚧 Future Improvements

* 🎨 GUI using SFML / Qt
* 🔊 Real audio playback integration
* 🤝 Collaborative filtering
* 🎼 Auto-generated playlists
* 🌐 Online metadata & album art fetching
* 🎧 Music visualizer

---

## 👤 Author

* RK Taseen
* Mahir Labib
* Samin Yasar
* Raed Rahman
---

## ⭐ Project Goal

PocketTrack demonstrates how **core software engineering concepts (OOP, file handling, system design)** can be applied to build a real-world application with both **offline functionality and intelligent recommendations**.

---

💡 *If you like this project, consider giving it a star!*
