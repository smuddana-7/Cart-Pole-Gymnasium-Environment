# CartPole Reinforcement Learning with PPO

This project demonstrates training and evaluating a reinforcement learning agent using the **Proximal Policy Optimization (PPO)** algorithm to balance a pole on a moving cart using the classic `CartPole-v0` environment from OpenAI Gymnasium.

## 📌 Project Structure

- `Cart_pole.ipynb`: Jupyter Notebook containing all code for training, evaluating, and visualizing the PPO agent's performance on CartPole.

## 🧠 What’s Inside

- Environment setup using `gymnasium` (CartPole-v0).
- Random agent interaction (baseline).
- Model training using PPO from `stable-baselines3`.
- Policy evaluation using `evaluate_policy`.
- Rendering and visualization of agent behavior.

## 🛠️ Installation

```bash
# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

## 🚀 How to Run

Open the notebook using Jupyter:

```bash
jupyter notebook Cart_pole.ipynb
```

Run each cell in sequence to observe training, evaluation, and rendering.

## 📈 Example Output

You will see episodes with scores, model training logs, and environment rendering showcasing the agent balancing the pole.

## 📚 References

- [Stable-Baselines3 Docs](https://stable-baselines3.readthedocs.io/)
- [OpenAI Gym CartPole](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py)
