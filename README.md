# Learning Game Project

*Automatically synced with your [v0.app](https://v0.app) deployments*

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/jirihofmans-projects/v0-learning-game-project-ss)
[![Built with v0](https://img.shields.io/badge/Built%20with-v0.app-black?style=for-the-badge)](https://v0.app/chat/420jwC35xMZ)

## Overview

An interactive programming learning game where players control a car on a 5×5 grid using simple commands (forward, left, right). This game teaches basic programming concepts like sequencing, planning, and problem-solving in a fun and visual way.

This repository stays in sync with your deployed chats on [v0.app](https://v0.app). Any changes you make to your deployed app will be automatically pushed to this repository.

## Features

### Game Modes

🚗 **Basic Mode**
- Navigate from a random start position to a random end position
- Plan your route and execute commands to reach the goal
- Perfect for learning basic movement and direction control

🍎 **Pick Food Mode**
- Start from the center of the board
- Collect randomly placed food items (🍎 🍌)
- Collect all food to win the game
- Great for practicing navigation and planning multiple destinations

🚧 **Obstacles Mode**
- Navigate from start to end while avoiding obstacles
- Random obstacles (🚧) are placed on the board
- Hitting an obstacle results in failure
- Teaches planning and obstacle avoidance strategies

### Controls

- **Forward** - Move the car one space forward in the current direction
- **Left** - Turn the car 90° counterclockwise
- **Right** - Turn the car 90° clockwise
- **Play** - Execute the sequence of commands
- **Clear** - Remove all commands and reset the car position
- **New Board** - Generate a new random board configuration

## Technology Stack

- **Framework**: Next.js 16.0.3 with React 19.2.0
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **Icons**: Lucide React
- **Deployment**: Vercel

## Local Development

### Prerequisites

- Node.js 18+ 
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/jirihofman/v0-learning-game-project.git

# Navigate to the project directory
cd v0-learning-game-project

# Install dependencies
npm install
# or
pnpm install
```

### Running the Development Server

```bash
npm run dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the game.

### Build for Production

```bash
npm run build
npm start
# or
pnpm build
pnpm start
```

### Linting

```bash
npm run lint
# or
pnpm lint
```

## Deployment

Your project is live at:

**[https://vercel.com/jirihofmans-projects/v0-learning-game-project-ss](https://vercel.com/jirihofmans-projects/v0-learning-game-project-ss)**

## Build your app

Continue building your app on:

**[https://v0.app/chat/420jwC35xMZ](https://v0.app/chat/420jwC35xMZ)**

## How It Works

1. Create and modify your project using [v0.app](https://v0.app)
2. Deploy your chats from the v0 interface
3. Changes are automatically pushed to this repository
4. Vercel deploys the latest version from this repository

## How to Play

1. **Select a game mode** - Choose between Basic, Pick Food, or Obstacles mode
2. **Plan your route** - Look at the board and figure out which commands you need
3. **Add commands** - Click the Forward, Left, and Right buttons to build your command sequence
4. **Execute** - Press the Play button to watch the car execute your commands
5. **Win or retry** - If you succeed, try a new board. If not, clear and try again!

## Contributing

This is a learning project built with v0.app. Feel free to fork and experiment with your own variations!