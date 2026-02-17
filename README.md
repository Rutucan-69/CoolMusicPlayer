# Music Player - DM Mono Edition

A sleek, minimalist web-based music player featuring a high-contrast dark aesthetic and a monospaced design language. Built with a focus on clean typography and functional geometry.

---

## Key Features

* **Folder-Based Playback**: Easily load an entire directory of music files at once using the "Select Folder" functionality.
* **Dynamic Visualizer**: Real-time frequency analysis powered by the Web Audio API, rendered on a dedicated canvas.
* **Metadata Integration**: Automatically extracts and displays embedded album artwork using the `jsmediatags` library.
* **Responsive Audio Controls**: Includes standard playback features: Play/Pause, Skip Forward/Back, Shuffle, Volume Control, and a Seekable Progress Bar.
* **Active Tracking**: Highlights the currently playing track in the playlist and displays the filename in the top status bar.

---

## Technical Stack

* **Frontend**: HTML5, CSS3 (Flexbox and Absolute Positioning).
* **Typography**: DM Mono via Google Fonts.
* **Audio Engine**: Web Audio API for visualization and the HTML5 `<audio>` element for playback.
* **External Libraries**: `jsmediatags` (CDN) for parsing ID3 tags and album art from music files.

---

## Design System

The interface follows a specific "Mono Edition" design token set:

| Property | Value |
| :--- | :--- |
| **Background** | `#141414` (Deep Charcoal) |
| **Accent Color** | `#b589d6` (Soft Lavender/Purple) |
| **Border Color** | `#4c4a4e` (Mid-Grey) |
| **Text Color** | `#4c4c4c` (Muted Grey) |
| **Font Main** | `'DM Mono'`, monospace |

---

## 🤖 AI Collaboration & Open Source

* **Development**: This project was developed with the assistance of **AI** to refine the functional geometry and technical implementation.
* **Open Source**: This software is **open source** and **free to use**. 
* **Usage**: You are free to modify, distribute, and adapt the code for personal or educational projects.

---

## Installation & Usage

1.  **Download/Clone**: Save the `index.html` file and ensure your icon assets (`play.png`, `pause.png`, `shuffle_off.png`, `back.png`, `forward.png`) are in the same directory.
2.  **Open**: Launch the file in any modern web browser (Chrome, Edge, or Firefox recommended for folder-access support).
3.  **Load Music**: Click the **SELECT FOLDER** button in the sidebar to populate your playlist.
4.  **Interact**: Click any track in the middle panel to start playback.

---

## Project Structure

* **Top Bar**: Displays the "Now Playing" status and simulated window controls.
* **Sidebar (Left)**: Houses the album art display, the real-time visual