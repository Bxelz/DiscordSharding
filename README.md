# Discord.js Sharding Guide

A simple and beginner-friendly guide on how to set up Discord.js sharding using the `ShardingManager` class.

## 📌 Prerequisites

- Node.js (latest LTS recommended)
- A Discord bot token
- `discord.js` installed
- Basic knowledge of JavaScript and Node.js

## 📂 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Bxelz/Discord-Sharding.git
```

### 2️⃣ Install Dependencies
```sh
npm install discord.js
```

### 3️⃣ Configure Your Bot
Create a `config.json` file in the root directory and add your bot token:
```json
{
    "token": "YOUR_BOT_TOKEN"
}
```
Alternatively, you can use environment variables for better security.

### 4️⃣ Sharding Manager Overview
The `Shards.js` file is responsible formanaging multiple shards of your bot, good performance and scalability. It initializes and monitors the shards, handling events such as launching, errors, and disconnections.

### 5️⃣ Running the Sharder
```sh
node Shards.js
```
This will automatically handle multiple shards based on Discord’s recommendations.

## 🔧 Handling Shard Events
The `Shards.js` file also includes event listeners for better monitoring:

---

⭐ Star the repo if this helped you!

📌 **Repo:** [Bxelz/Discord-Sharding](https://github.com/Bxelz/Discord-Sharding)

