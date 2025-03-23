markdown
# Text-Based-Console-Football

![License](https://img.shields.io/badge/License-GNU-blue.svg)

## Description

**Text-Based-Console-Football** is a simple text-based football (soccer) game implemented in **C++**. The game simulates a 15-round match between two teams, where players can control the flow of the game using basic commands. This project is designed to help practice C++ programming skills, including object-oriented programming, user input handling, and game logic implementation.

## Features

- **Text-Based Interface**: The game runs entirely in the console, making it lightweight and easy to run on any system.
- **15-Round Match**: The game consists of 15 rounds, with each team taking turns to perform actions.
- **Two Teams**: Two teams compete against each other, and users can input custom team names.
- **Basic Game Logic**: Includes football rules such as scoring, fouls, and match progression.
- **Simple Commands**: Users can interact with the game using straightforward text commands.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SyedMuhammadSajawalHussain/Text-Based-Console-Football.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Text-Based-Console-Football
   ```

3. **Compile the C++ code**:
   ```bash
   g++ -o football_game main.cpp
   ```

4. **Run the game**:
   ```bash
   ./football_game
   ```

   *Note*: Ensure you have a C++ compiler (e.g., `g++`) installed on your system.

## Usage

Once the game is running, follow the on-screen instructions to start a match. You will be prompted to enter the names of the two teams. During the match, each team will take turns to perform actions in 15 rounds. Available commands include:

- `shoot`: Attempt to score a goal.
- `pass`: Pass the ball to another player.
- `tackle`: Attempt to tackle an opponent.
- `foul`: Commit a foul (risky!).
- `status`: Check the current match status (score, round, etc.).

The game will simulate the match based on your commands and provide feedback on the outcome of each action. At the end of 15 rounds, the game will declare the winner or if the match is a draw.

## Example Gameplay

```
Welcome to Text-Based-Console-Football!
Enter Team 1 name: Red Dragons
Enter Team 2 name: Blue Tigers

Match started: Red Dragons vs Blue Tigers

Round 1:
Red Dragons' turn. Choose action (shoot/pass/tackle/foul/status): shoot
Red Dragons scored a goal! Score: 1-0

Round 2:
Blue Tigers' turn. Choose action (shoot/pass/tackle/foul/status): pass
Blue Tigers passed the ball. No score change.

...

Round 15:
Red Dragons' turn. Choose action (shoot/pass/tackle/foul/status): shoot
Red Dragons missed the goal! Score remains 3-2.

Match ended! Final Score: Red Dragons 3 - 2 Blue Tigers
Red Dragons wins!
```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

Please ensure your code follows the project's coding standards and includes appropriate documentation.

## License

This project is licensed under the **GNU General Public License**. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Name**: Syed Muhammad Sajawal Hussain
- **GitHub Profile**: [SyedMuhammadSajawalHussain](https://github.com/SyedMuhammadSajawalHussain)
- **WhatsApp**: [+92 328 0841432](https://wa.me/923280841432)
- **Email**: [syedmuhammadsajawalhussain002@gmail.com](mailto:syedmuhammadsajawalhussain002@gmail.com)

---

Enjoy the game! ⚽
