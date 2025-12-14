# 🦸‍♂️ Flappy Iron Man

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pygame](https://img.shields.io/badge/Pygame-2.x-green?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

> 🏆 **AWARD WINNER:** 1st Place at the University Software Development Competition (Selected among 24 participating teams).

# This project was created as a group effort with Adam, Alex, and David during a one-week basic programming practice session in the Introduction to Programming course at the University of Mainz.

# If you have any questions or suggestions for improvements regarding the published game, please feel free to write to us

## 📄 Project Overview

**Flappy Iron Man** is an advanced reinterpretation of the classic arcade genre, built entirely in **Python** using the **Pygame** engine. Unlike the original, this project introduces strategic combat mechanics: the player controls Iron Man, collecting coins to gain ammunition and destroy obstacles (walls), rather than just dodging them.

The project demonstrates a strong understanding of **Object-Oriented Programming (OOP)**, collision detection algorithms, and game state management.

## ✨ Key Features

* **Combat System:** Collect coins to charge the repulsor beam. Shoot down walls to clear your path.
* **Dynamic Difficulty:** An algorithm adjusts the spawn rate of obstacles based on the player's score.
* **Destructible Environment:** Walls have health points and require multiple hits to break.
* **Multimedia Integration:** Includes a video intro and dynamic sound effects.
* **OOP Architecture:** Modular code structure using Sprite classes for scalability.

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

* Python 3.x installed.
* `pip` package manager.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/flappy-iron-man.git](https://github.com/YOUR_USERNAME/flappy-iron-man.git)
    cd flappy-iron-man
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the game:**
    ```bash
    python main.py
    ```

## 📂 Project Structure

The project follows a modular architecture to separate logic from assets:

```text
├── Assets/                 # Images, Sounds, and Video files
├── files/                  # Source code modules
│   ├── character_class.py  # Player physics and logic
│   ├── wand_class.py       # Obstacle generation and behavior
│   ├── score.py            # Scoring system
│   └── ...                 # Other helper classes
├── main.py                 # Entry point and Game Loop
└── requirements.txt        # Dependencies