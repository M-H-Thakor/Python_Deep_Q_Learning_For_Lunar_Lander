# 🚀 Python Deep Q-Learning for Lunar Lander

This project implements a Deep Q-Learning (DQN) agent to master the **LunarLander-v3** environment using **PyTorch** and **OpenAI Gymnasium**. The agent learns to land a spacecraft between landing flags using reinforcement learning.

---

## 🧠 Key Features

- 🕹️ **Environment**: LunarLander-v3 from Gymnasium (Box2D physics-based).
- 🤖 **Deep Q-Network (DQN)**: With fully connected layers, experience replay, and soft target updates.
- 🎯 **Epsilon-Greedy Strategy**: For a balanced exploration-exploitation trade-off.
- 💾 **Experience Replay Buffer**: Stores past interactions to stabilize training.
- 📈 **Progress Tracking**: Monitors average score across episodes.
- 📽️ **Video Playback**: Renders trained agent’s landing skills (see below).

---

## 📽 Demo Video

Watch the trained agent successfully land the lunar module in the simulation:

> ⚠️ Ensure the video file `demo_video.mp4` is in your repo folder or hosted online for GitHub preview.

[![Demo Video](demo_video.mp4)](demo_video.mp4)

---

## 📂 Project Structure

- `deep_q_learning_for_lunar_landing.py`: Main implementation of the DQN training pipeline.
- `Network`: Neural network for Q-value approximation.
- `ReplayMemory`: Experience replay logic.
- `Agent`: Handles action selection, training, and model updates.
- `show_video_of_model`: Captures and plays trained agent’s gameplay.

---

## 🛠 Requirements

Install the dependencies using pip:

```bash
pip install gymnasium[box2d] torch numpy imageio
