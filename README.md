# 🐦 Flappy Bird Game using Gymnasium

An AI-powered Flappy Bird game built using **Python**, **Gymnasium**, and **Reinforcement Learning** concepts. This project demonstrates how an AI agent learns to play Flappy Bird by interacting with the environment and improving its performance through training.

---

## 🚀 Features

- 🎮 Flappy Bird environment using Gymnasium
- 🤖 AI agent trained using Reinforcement Learning
- 📈 Training and evaluation support
- 💾 Save and load trained models
- 📊 Reward tracking and performance monitoring
- 🖥️ Simple and interactive gameplay visualization

---

## 🛠️ Technologies Used

- Python 3.x
- Gymnasium
- PyTorch
- NumPy
- Pygame (if used)

---

## 📂 Project Structure

```
Flappy_bird_game/
│
├── game_flappy_bird.py      # Main game
├── agent.py                 
├── dqn.py              
├── experience_replay.py                 
├── parameters.yaml                                 
```

## Screenshot
```
<img width="375" height="677" alt="image" src="https://github.com/user-attachments/assets/7ab83770-b8d7-426d-8d84-d57198c5945f" />

```
## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Anjali-Navgire/flappyBird_Game.git
```

### 2. Navigate to the project

```bash
cd flappyBird_Game
```

### 3. Create a virtual environment (Optional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install 
```

---

## ▶️ Running the Game

```bash
python game_flappy_bird.py
```

---

## 🧠 Training the AI

```bash
python agent.py flappybirdv0 --train  
```

The agent will learn by interacting with the environment and gradually improve its gameplay.

---

## 🎯 Testing the Trained Model

```bash
python agent.py flappybirdv0 
```

---

## 📈 Reinforcement Learning Workflow

```
Environment
      │
      ▼
Observe State
      │
      ▼
Choose Action
      │
      ▼
Take Action
      │
      ▼
Receive Reward
      │
      ▼
Update Policy
      │
      ▼
Repeat Until Training Completes
```

## 📚 Learning Objectives

This project helped in understanding:

- Reinforcement Learning
- Deep Q Networks (DQN)
- Gymnasium Environment
- Neural Networks with PyTorch
- Agent-Environment Interaction
- Reward Optimization

---

## 🔮 Future Improvements

- Double DQN
- Dueling DQN
- Prioritized Experience Replay
- PPO Implementation
- Better Graphics
- Hyperparameter Tuning
- Web Deployment

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

---

## 👩‍💻 Author

**Anjali Navgire**

- GitHub: https://github.com/Anjali-Navgire
- LinkedIn: https://www.linkedin.com/in/anjali-navgire

---

### Happy Coding! 🚀
