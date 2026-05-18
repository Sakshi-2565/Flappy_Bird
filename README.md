# 🐦 Flappy Bird AI using DQN

A Reinforcement Learning project where an AI learns to play **Flappy Bird** using **Deep Q-Networks (DQN)** with **PyTorch** and **Gymnasium**.

---

## 🎮 Demo

![Flappy Bird Demo](https://technologizer.com/wp-content/uploads/2014/06/flappybird.gif)


---

## 📌 Features

- Deep Q-Learning (DQN)
- Experience Replay Memory
- Target Network Synchronization
- Epsilon-Greedy Exploration
- PyTorch Neural Network
- Manual & AI Gameplay Support

---

## 📂 Project Structure

```bash
.
├── agent.py
├── DQN.py
├── experience_replay.py
├── game_flappy_bird.py
├── parameters.yaml
├── runs/
└── README.md
```

---

## 📖 File Description

### `agent.py`
Handles:
- Training loop
- Testing loop
- Environment interaction
- Model saving/loading

### `DQN.py`
Defines the Deep Q-Network architecture.

### `experience_replay.py`
Implements replay memory for storing experiences.

### `game_flappy_bird.py`
Allows manual gameplay using keyboard controls.

### `parameters.yaml`
Stores hyperparameters like:
- Learning rate
- Gamma
- Epsilon decay
- Batch size

---

## ⚙️ Installation

```bash
https://github.com/Sakshi-2565/Flappy_Bird.git
cd Flappy_Bird
```

Install dependencies:

```bash
pip install torch gymnasium flappy-bird-gymnasium pygame pyyaml
```

---

## 🚀 Train the Model

```bash
python agent.py flappybirdv0 --train
```

---

## ▶️ Test the Trained AI

```bash
python agent.py flappybirdv0
```

---

## 🎮 Play Manually

```bash
python game_flappy_bird.py
```

Press `SPACE` to flap.

---

## 📈 Output Files

Trained model:

```bash
runs/flappybirdv0.pt
```

Training logs:

```bash
runs/flappybirdv0.log
```

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Gymnasium
- PyGame
- YAML

---

## ⭐ Future Improvements

- Double DQN
- Dueling DQN
- TensorBoard visualization
- Better reward shaping

---
