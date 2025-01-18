# Reinforcement Flappy Bird 🐦

A Python-based implementation of the classic Flappy Bird game, enhanced with reinforcement learning using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The AI learns to play the game by evolving through generations, improving its performance over time.

---

## 🚀 Features
- **NeuroEvolution**: Trains birds to learn from their mistakes and improve their gameplay across generations.
- **Dynamic Environment**: Includes moving pipes and an animated bird character.
- **Customizable Fitness Function**: Fine-tune the fitness parameters to optimize AI training.
- **Built with Python**: Utilizes popular libraries like `pygame` and `neat-python`.

---

### Key Files:
- **`main.py`**: The main script containing the game logic and NEAT implementation.
- **`configuration_file_project.txt`**: NEAT configuration file for managing neural network parameters.
- **`imgs/`**: Contains all the assets for the game (bird, pipes, base, and background).

---

## 🎮 How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HarshKumar67/Reinforcement-flappy.git
   cd Reinforcement-flappy

## ⚙️ How It Works

### Game Mechanics:
- The bird moves through pipes while avoiding collisions.
- The base scrolls to simulate continuous motion.

### AI Training:
- The AI uses the NEAT algorithm to evolve neural networks for controlling the bird.
- Fitness is calculated based on survival time and successful pipe navigation.

### Inputs to the Neural Network:
- Bird's vertical position.
- Distance from the next pipe (top and bottom).

### Outputs from the Neural Network:
- A single value indicating whether the bird should jump.

---

## 🛠️ Customization
- **Adjusting Fitness**: Modify the `ge[x].fitness` values in `main.py` to control how the AI rewards survival and penalizes collisions.
- **Changing Pipe Gap**: Edit the `gap` attribute in the `Pipe` class to make the game easier or harder.

---

## 📸 Screenshots

![Screenshot 2025-01-19 001733](https://github.com/user-attachments/assets/86ba3052-ea3d-4a0f-a6a1-9430a51d016a)

---

## 🌟 Features to Explore
- Improve the fitness function to train the bird faster.
- Add new obstacles or challenges for the AI to overcome.
- Explore hyperparameter tuning in the `configuration_file_project.txt`.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

---

## 📝 License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it.

---

## 📧 Contact
If you have any questions or suggestions, feel free to reach out:

- **GitHub**: [HarshKumar67](https://github.com/HarshKumar67)
- **Email**: [harshero03@gmail.com]
