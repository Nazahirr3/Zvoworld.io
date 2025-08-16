# zvoworld.io

A browser-based multiplayer evolution game, inspired by EvoWorld.io.

## Overview

zvoworld.io is a real-time online game where you control a creature that must eat food and other players to grow, evolve, and survive. The game features diverse biomes, evolution stages, unique abilities, and competitive multiplayer gameplay.

## Features

- **Evolution System**: Progress through multiple stages; each form has unique abilities, strengths, and weaknesses.
- **Food & Items**: Consume various foods and special items to gain XP or temporary powers.
- **Biomes & Maps**: Explore distinct regions (grassland, jungle, desert, arctic, sky, underground, cosmic, etc.), each with unique hazards and resources.
- **Structures & Objects**: Interact with map objects like barriers, tombstones, castles, city buildings, igloos, and more.
- **Status Effects & Skills**: Gain effects from items, biomes, or evolution (e.g., speed boost, poison, fire, etc.).
- **Multiplayer**: Real-time competitive gameplay, spectating, friends, chat, and revival mechanics.
- **Pets & NPCs**: Encounter pets and non-player creatures with unique behaviors.
- **Account & Cosmetics**: Skins, premium accounts, bonus codes, and friend features.

## Getting Started

1. **Install dependencies**  
   ```bash
   npm install
   ```

2. **Run development server**  
   ```bash
   npm run dev
   ```

3. **Open in browser**  
   Go to [http://localhost:3000](http://localhost:3000)

## Tech Stack

- **TypeScript**
- **Phaser.js** (or similar game engine)
- **WebSocket** for multiplayer networking
- **Node.js** for server-side logic (to be added)

## Development Structure

- `public/`: Static assets like sprites, tilesets, audio.
- `src/`: Game logic, entities, mechanics, UI, networking.
- `config/`: Game configuration, such as level progression, mob stats.
- `tests/`: Automated testing.

## Contributing

1. Fork the repo and create a new branch.
2. Submit a pull request with a clear description.
3. See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## License

MIT
