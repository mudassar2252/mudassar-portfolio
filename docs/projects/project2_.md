# 🤖 PPO on CartPole-v1

This project involves implementing the **Proximal Policy Optimization (PPO)** algorithm from scratch using **PyTorch** and **Gymnasium** to solve the CartPole-v1 environment.

- **🧠 Algorithm:** PPO (Proximal Policy Optimization)
- **🛠️ Tech Stack:** Python, PyTorch, Gymnasium
- **📁 GitHub Repository:** [View on GitHub](https://github.com/mudassar2252/Reinforcement)

---

## 🎯 Objectives

- Understand and implement PPO.
- Apply PPO to the CartPole-v1 task.
- Analyze learning behavior and compare with other methods (e.g., A2C, DQN).
  
---

## 🧪 Key Features

- **Actor-Critic Architecture:** Two neural networks (policy + value function).
- **Clipped Objective:** Prevents destructive policy updates.
- **Advantage Estimation:** Improves learning direction and efficiency.
- **Entropy Bonus:** Optional, encourages better exploration.

---

## 🏗️ Implementation Highlights

### 🔹 Network Structure

- Input: 4 neurons (CartPole state features)
- Hidden Layers: 2 × 128 neurons (ReLU)
- Output: 2 neurons (actor) / 1 neuron (critic)

### 🔹 Training Pipeline

1. Collect episode trajectories  
2. Compute discounted rewards and advantages  
3. Apply PPO updates with clipped surrogate objective  
4. Repeat for 500 episodes or until convergence

---

## 📈 Results

- **Converged around:** Episode 140–160  
- **Average Reward:** Surpassed 400  
- **Reward Plot:** Smooth with minimal oscillation  
- **Max Y-Axis:** Customized to 2500 for clarity  

---

## 🏆 PPO Advantages

- ✅ **Fast Convergence**
- ✅ **Stable Training**
- ✅ **Simple Tuning**
- ✅ **Effective Policy Learning**

---

## 📌 Conclusion

PPO effectively solved the CartPole-v1 problem with better speed and stability than A2C or DQN. This project enhanced understanding of modern policy-gradient methods and demonstrated PPO’s strength in real-world environments.

