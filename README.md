
# RL Notebooks (Q-Learning, DQN, PPO, A2C, Comparison)

This bundle contains five Jupyter notebooks with thorough **Markdown explanations before each code cell**.

## Contents
- `01_Q_Learning.ipynb` — **Tabular Q-Learning** on a discrete env (FrozenLake or CliffWalking).
- `02_DQN.ipynb` — **Deep Q-Network** (discrete actions) using Stable Baselines3 on CartPole.
- `03_PPO.ipynb` — **Proximal Policy Optimization** with vectorized envs.
- `04_A2C.ipynb` — **Advantage Actor-Critic** (on-policy).
- `05_Comparison.ipynb` — Train or load models and **compare** learning curves, returns.

## Quick Start
1. Create/activate a Python 3.10+ venv.
2. `pip install -r requirements.txt`
3. Launch Jupyter: `jupyter lab` (or `jupyter notebook`)
4. Open any notebook and run the cells top to bottom.

## References
- Gymnasium docs: https://gymnasium.farama.org/
- Stable Baselines3 docs: https://stable-baselines3.readthedocs.io/en/master/

> Tip: For reproducibility, keep seeds fixed and versions pinned.
