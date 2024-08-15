# InfernoDog Dash Game

Welcome to the **InfernoDog Dash Game** repository! This project is a 2D game developed using JavaScript, HTML5 Canvas, and other modern web technologies. The game features a fiery dog character that chases and burns enemies with unique behaviors, challenging the player to survive as long as possible.
![alt text](Game-1.png)
## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Demo
You can check out a live demo of the game [here](https://2d-jsgame.netlify.app/).

## Features
- **Enemies**: Various enemies with different behaviors:
  - Flying enemies that move in a sine wave pattern.
  - Ground enemies that move horizontally on the ground.
  - Climbing enemies that move vertically, changing direction when hitting boundaries.
- **Animations**: Smooth animations for each enemy type, controlled by frame timing.
- **Game Loop**: Efficient game loop handling rendering and updating of entities.
- **Responsive Design**: The game adjusts to different screen sizes.
- **Fiery Dog Character**: Control a dog with fiery abilities, capable of burning enemies.

## Installation

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).

### Clone the Repository
```bash
git clone https://github.com/yourusername/InfernoDogDashGame.git
cd InfernoDogDashGame
```

### Run the Game
1. **Using a local server (recommended):**
   ```bash
   npx http-server .
   ```
   Open your browser and go to `http://localhost:8080`.

2. **Or simply open `index.html` in your browser:**
   - Navigate to the project directory.
   - Double-click `index.html`.

## Usage
- Use arrow keys to move the dog character.
- Press the spacebar to perform a fiery dash to burn enemies.
- Avoid or eliminate enemies to stay alive as long as possible.
- Track your score and try to beat your high score!

## Project Structure
```
/InfernoDogDashGame
│
├── /assets           # Game assets (images, sounds, etc.)
├── /css              # CSS stylesheets
├── /js
│   ├── enemies.js    # Enemy classes and behaviors
│   ├── background.js # Background rendering and animation
│   ├── main.js       # Main game logic and loop
│   └── utils.js      # Utility functions
├── index.html        # Entry point for the game
└── README.md         # This file
```

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request. Please make sure to follow the project's coding standards and conventions.

### To Contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch-name`).
6. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please contact:
- **Shivam Kumar Pathak** - [shivampathak0123456@gmail.com](mailto:shivampathak0123456@gmail.com)
- GitHub: [shivampathak4](https://github.com/shivampathak4)

---

Thank you for checking out InfernoDog Dash Game! Enjoy playing!


