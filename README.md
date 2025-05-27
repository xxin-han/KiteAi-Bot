# KiteAi-Bot

**Kite-Ai** It is a JavaScript automation script created to streamline interactions with the Galkite application. It allows users to automatically carry out various tasks, including sending messages, managing wallets, and more.

## Features

- Automated message sending via `message_professor.txt & message_cryptobuddy.txt`.
- Automatic wallet management using Private key on `accounts.txt`.
- Proxy support via `proxy.txt`.
- Easy configuration through `package.json`.

## Installation

1. Make sure you have [Node.js](https://nodejs.org/) installed on your system.
2. Install Tools.
   ```bash
   wget https://github.com/xxin-han/setup/raw/main/setup.sh -O setup.sh && chmod +x setup.sh && ./setup.sh
   ```
3. Clone this repository:
   ```bash
   git clone https://github.com/xxin-han/KiteAi-Bot.git
   ```
4. Navigate to the project directory:
   ```bash
   cd KiteAi-Bot
   ```
5. Install the required dependencies:
   ```bash
   npm install
   ```
6. Fill the private key list on accounts.txt then save it ctrl + x + y + enter
   ```bash
   nano accounts.txt
   ```
7. run it
   ```bash
   npm start
   ```
8. Stop bot

   ctrl + c
