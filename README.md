# Mope.io Fanmade Game

## Overview
This project is a fanmade game inspired by mope.io, where players control animals in a competitive environment, eating food and growing in size while avoiding larger predators. The game features both client-side and server-side components, allowing for real-time multiplayer interactions.

## Project Structure
```
mopeio-fanmade-game
├── src
│   ├── client
│   │   ├── index.html
│   │   ├── styles
│   │   │   └── main.css
│   │   └── scripts
│   │       └── main.js
│   ├── server
│   │   ├── server.ts
│   │   └── game
│   │       ├── gameLogic.ts
│   │       └── player.ts
│   └── shared
│       └── types.ts
├── package.json
├── tsconfig.json
└── README.md
```

## Setup Instructions
1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/mopeio-fanmade-game.git
   cd mopeio-fanmade-game
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the server:**
   ```
   npm run start
   ```

4. **Open the game in your browser:**
   Navigate to `http://localhost:3000` to start playing.

## Gameplay
- Players start as small animals and must eat food items to grow larger.
- Avoid larger players to survive and continue growing.
- The game features various animal types, each with unique abilities.
- Players can interact with each other, forming alliances or competing for resources.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is not affiliated with the original mope.io game and is intended for educational and entertainment purposes only.