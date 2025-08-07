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

```

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Python_Deep_Q_Learning_For_Lunar_Lander.git
   cd Python_Deep_Q_Learning_For_Lunar_Lander
   ```

2. Install the dependencies:
   ```bash
   pip install gymnasium[box2d] torch numpy imageio
   ```

3. Run the main script:
   ```bash
   python deep_q_learning_for_lunar_landing.py
   ```

4. After training, the agent’s gameplay video will be saved as `demo_video.mp4`.


## 📊 Sample Output

```
Episode 100    Average Score: 120.35
Episode 200    Average Score: 202.56
Environment solved in 195 episodes! Average Score: 200.01
```


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
