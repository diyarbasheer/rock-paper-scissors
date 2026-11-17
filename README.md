# ✊✋✌️ AI Rock Paper Scissors | Markov Engine

A real-time, camera-based **Rock-Paper-Scissors** web game powered by **MediaPipe Hands**, **FastAPI**, and **Tailwind CSS**. Play using live hand gestures via your webcam while an adaptive **Markov Chain** AI learns your patterns and predicts your next move[cite: 4].

---

## ✨ Features

- **Real-Time Hand Tracking:** Uses **MediaPipe** computer vision directly in the browser to detect Rock, Paper, and Scissors gestures from your webcam[cite: 4].
- **3 AI Difficulty Levels:**
  - **Easy:** Plays completely random moves[cite: 4].
  - **Medium:** Tracks your most frequently used move and counters it[cite: 4].
  - **Impossible (Markov Chain):** Learns your move sequences and predicts your next choice with live confidence percentages[cite: 4].
- **Live AI Thought Insights:** Displays the AI's real-time reasoning and prediction logic after every round[cite: 4].
- **Scoreboard & Move History:** Tracks player wins, AI wins, draws, and your recent move sequence with a one-click reset option[cite: 4].

---

## 🚀 How to Run

1. **Install dependencies:**
   ```bash
   pip install fastapi uvicorn jinja2