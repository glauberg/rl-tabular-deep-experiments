# Experimentos de Aprendizado por Reforço: Métodos Tabulares e Profundos (Deep RL)

Repositório público contendo as implementações, execuções completas, curvas de treinamento e vídeos dos experimentos comparativos de **Aprendizado por Reforço Tabular (Q-learning e SARSA)** e **Aprendizado por Reforço Profundo (DQN e Target/Double DQN com MLP e CNN)**.

## Notebooks Implementados

| # | Notebook | Algoritmo(s) | Ambiente (Gymnasium) | Acesso Direto GitHub | Executar no Google Colab |
|---|---|---|---|---|---|
| 0 | `Introducao_Gymnasium.ipynb` | Agente Aleatório / Wrappers | `CartPole-v1` | [Ver no GitHub](https://github.com/glauberg/rl-tabular-deep-experiments/blob/main/Introducao_Gymnasium.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/glauberg/rl-tabular-deep-experiments/blob/main/Introducao_Gymnasium.ipynb) |
| 1 | `01_Q_learning_SARSA_Tabular_FrozenLaken.ipynb` | Q-learning & SARSA (Tabular) | `FrozenLake-v1` ($8\times 8$, determinístico e escorregadio) | [Ver no GitHub](https://github.com/glauberg/rl-tabular-deep-experiments/blob/main/01_Q_learning_SARSA_Tabular_FrozenLaken.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/glauberg/rl-tabular-deep-experiments/blob/main/01_Q_learning_SARSA_Tabular_FrozenLaken.ipynb) |
| 2 | `02_Q_learning_SARSA_Tabular_Blackjack.ipynb` | Q-learning & SARSA (Tabular) | `Blackjack-v1` (`sab=True` e `natural=True`) | [Ver no GitHub](https://github.com/glauberg/rl-tabular-deep-experiments/blob/main/02_Q_learning_SARSA_Tabular_Blackjack.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/glauberg/rl-tabular-deep-experiments/blob/main/02_Q_learning_SARSA_Tabular_Blackjack.ipynb) |
| 3 | `Deep_Q_Learning_CartPole.ipynb` | Deep Q-Learning (MLP) | `CartPole-v1` | [Ver no GitHub](https://github.com/glauberg/rl-tabular-deep-experiments/blob/main/Deep_Q_Learning_CartPole.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/glauberg/rl-tabular-deep-experiments/blob/main/Deep_Q_Learning_CartPole.ipynb) |
| 4 | `Double_Deep_Q_Learning_CartPole.ipynb` | Double / Target Deep Q-Learning (MLP) | `CartPole-v1` | [Ver no GitHub](https://github.com/glauberg/rl-tabular-deep-experiments/blob/main/Double_Deep_Q_Learning_CartPole.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/glauberg/rl-tabular-deep-experiments/blob/main/Double_Deep_Q_Learning_CartPole.ipynb) |
| 5 | `Double_Deep_Q_Learning_SpaceInvaders.ipynb` | Double / Target Deep Q-Learning (CNN + MLP) | `SpaceInvadersNoFrameskip-v4` (Atari) | [Ver no GitHub](https://github.com/glauberg/rl-tabular-deep-experiments/blob/main/Double_Deep_Q_Learning_SpaceInvaders.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/glauberg/rl-tabular-deep-experiments/blob/main/Double_Deep_Q_Learning_SpaceInvaders.ipynb) |

## Execução Local

```bash
python -m venv .venv
source .venv/bin/activate
pip install "gymnasium[toy-text,classic-control]>=1.0,<2.0" torch numpy matplotlib seaborn imageio imageio_ffmpeg tqdm
```
