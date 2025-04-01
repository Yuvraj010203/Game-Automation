# Game Automation- Chrome Dino
This project automates gameplay for the Chrome Dino game using computer vision and reinforcement learning. It captures game frames in real time, processes them for obstacle detection, and performs corresponding actions like jumping or ducking. The project integrates a reinforcement learning agent using Stable Baselines3 (DQN) to optimize decision-making and improve gameplay performance.


## Tech Stack

🔹 Python
🔹 OpenCV
🔹 mss (for screen capture)

🔹 PyDirectInput (for keyboard automation)

🔹 Pytesseract (for game-over detection)

🔹 Matplotlib (for visualization)

🔹 Gymnasium (for reinforcement learning environment)

🔹 Stable Baselines3 (DQN) (for AI model training)
## Features

- Captures real-time game frames and processes them for AI training.

- Automates Chrome Dino gameplay using keyboard inputs mapped to actions.

- Recognizes game-over events through OpenCV image processing and OCR (Tesseract).

- Implements a reinforcement learning (DQN) agent to optimize performance.

- Uses Gymnasium to create a custom environment for AI interaction.

- Trains the model with Stable Baselines3, logging progress and saving checkpoints

