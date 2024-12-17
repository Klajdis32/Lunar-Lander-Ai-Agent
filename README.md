# **Lunar Lander Project**

## **Project Overview**
This project focuses on training an agent to successfully land a lunar module on the flattest possible surface to avoid damage. The agent is trained using Reinforcement Learning (RL) techniques, specifically with the **Proximal Policy Optimization (PPO)** algorithm implemented in **Ray RLlib**.

## **Objective**
The goal is to train the agent to:
1. **Control the lunar lander** efficiently.
2. **Land safely** on a flat surface with minimal damage.
3. Optimize the reward function during training.

## **Files Included**
- **`LunarLander.ipynb`**: This notebook contains the full implementation, explanation, and results of the project. It includes:
  - Initialization of the environment and agent.
  - Training the agent with specified hyperparameters.
  - Visualizing the training performance.
  - Testing the agent for multiple landing attempts.
- **`lunarlander_combined_best.mp4`**: A video showcasing the **top 3 landings** performed by the trained agent.

## **Technologies Used**
- **Python**: Programming language used for implementation.
- **Ray RLlib**: Library for Reinforcement Learning.
- **Gymnasium**: Environment for Lunar Lander simulation.
- **MoviePy** and **ImageIO**: Used for video generation and processing.
- **PyTorch**: Framework for neural networks in PPO training.

## **How It Works**
1. The agent interacts with the **LunarLander-v3** environment.
2. It is trained over **100 iterations** to maximize cumulative rewards, with each reward corresponding to smooth landings and minimal damage.
3. The **best 3 landings** are recorded and combined into a single video file.

## **Results**
The video `lunarlander_combined_best.mp4` displays the **3 best landings** achieved by the trained agent, demonstrating its ability to land the lunar module safely.

---

## **How to Run**
You can run the project on **Google Colab** by following these steps:

1. **Create a Google Account** (if you don’t already have one) and go to [Google Colab](https://colab.research.google.com/).
2. **Upload the Code**:
   - Download the file **`LunarLander.ipynb`** from this repository.
   - Upload it to Google Colab by clicking **“File” → “Upload notebook”**.
3. **Run the Code Step-by-Step**!