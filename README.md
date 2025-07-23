# CartPolePPO

## 🎯 Project Overview
This repository contains an implementation of Proximal Policy Optimization (PPO) for the CartPole-v1 environment using PyTorch and Gymnasium.

## ⚙️ Setup & Installation
1. **Clone the repo**
   ```bash
   git clone https://github.com/<your-username>/CartPolePPO.git
   cd CartPolePPO
   ```
2. **Create & activate a virtual environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate      # on Windows: .venv\Scripts\activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage
- **Train the agent**
  ```bash
  python CartPolePPO.py --train
  ```
- **Evaluate a trained model**
  ```bash
  python CartPolePPO.py --play --model-path checkpoint/ppo_cartpole.pt
  ```

## 📁 File Structure
```
CartPolePPO/
├── ActorCritic.py       # Actor & Critic network definitions
├── Network.py           # Shared neural network architecture
├── CartPolePPO.py       # Main training/evaluation script
├── checkpoint/          # Saved model weights (.pt)
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── .gitignore           # Git ignore rules
```

## ⚖️ License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
