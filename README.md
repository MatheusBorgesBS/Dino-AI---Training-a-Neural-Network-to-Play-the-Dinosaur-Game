# Dino AI - Training a Neural Network to Play the Dinosaur Game (Still Working)

This repository contains an environment developed in **Pygame** to simulate the dinosaur game and train a **neural network** to play it automatically. The AI training will be done using **TensorFlow**, utilizing either reinforcement learning or supervised learning.

## 📌 Objective
Create an intelligent agent that learns to play the dinosaur game, jumping over obstacles at the right time to maximize its score.

## 🚀 Technologies Used
- **Python** 🐍
- **Pygame** (for game environment simulation) 🎮
- **TensorFlow/Keras** (for building and training the neural network) 🧠
- **NumPy and Pandas** (for data manipulation) 📊

## 🔧 Project Structure
```
📂 dino-ai
│── 📝 README.md
│── 📄 dino_game.py  # Game code
│── 📄 train_ai.py   # AI training code (when available)
│── 📄 model.h5      # Trained model (when available)
│── 📂 assets        # Game sprites and images (if any)
```

## 📖 How to Run the Project
1. **Install dependencies**:
   ```bash
   pip install pygame tensorflow numpy pandas
   ```
2. **Run the game manually**:
   ```bash
   python dino_game.py
   ```
3. **Train the AI**:
   ```bash
   python train_ai.py
   ```
4. **Test the AI playing**:
   ```bash
   python dino_game.py --ai
   ```

## 🏗️ Next Steps
- Implement an agent using **reinforcement learning (Deep Q-Learning)**
- Improve training efficiency
- Add graphs to visualize AI progress

Feel free to contribute! 🚀

