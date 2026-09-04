> [!WARNING]
> **This project has been archived.**
>
> Active development, improvements, bug fixes, and feature updates have been discontinued.
>
> The project will remain publicly available, and you are **free to use, fork, and modify it** according to the project's license. However, no further updates or official support are planned.

<div align="center">

# ✨ ASTRYX


### The Ultimate Multipurpose Discord Bot

A powerful, fast, and feature-rich Discord bot built with **discord.js v14**.

[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white)]()
[![Discord.js](https://img.shields.io/badge/discord.js-v14-5865F2?style=for-the-badge&logo=discord&logoColor=white)]()
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?style=for-the-badge&logo=postgresql&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MELON%20OSL-purple?style=for-the-badge)]()

*Built for communities of every size.*

</div>

---

# ✨ Features

ASTRYX combines everything you need into one powerful Discord bot.

| Category | Description |
| :-------- | :---------- |
| 🛡️ Moderation | Ban, Kick, Mute, Timeout, Lock, Unlock, Slowmode, Tempban, Softban |
| ⚔️ Antinuke | Advanced protection against raids and malicious actions |
| 🚔 Automod | Automatic spam, invite, scam and abuse protection |
| 🎵 Music | High-quality music powered by Lavalink |
| 🤖 AI | AI chat, image analysis and smart utilities |
| 🎫 Tickets | Fully configurable support ticket system |
| 🎭 Reaction Roles | Self-assignable roles using reactions |
| 👋 Welcome | Custom welcome and farewell messages |
| 📝 Logging | Comprehensive server logging |
| 🎁 Giveaways | Create and manage giveaways |
| 📊 Statistics | Server and user statistics |
| 😄 Fun | Memes, Truth or Dare, Roleplay, Fake Messages |
| 🔍 Utility | Avatar, Banner, User Info, Server Info, Ping and more |
| 📁 Export | Export channels, members, roles and server data |
| 🔄 Converters | Unit, Base, Text and Encoding converters |
| 🐾 Animals | Random adorable animal pictures |
| 💰 Crypto | Cryptocurrency prices and information |
| 📚 Wikipedia | Search Wikipedia instantly |
| 📰 News | Latest news headlines |

---

# 🚀 Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd ASTRYX
```

### 2. Install dependencies

```bash
npm install
```

### 3. Emoji Copy

Emoji Sync

```bash
node scripts/upload-application-emojis.js --write-source 
```

Edit `.env` with your credentials.

```env
DISCORD_TOKEN=
CLIENT_ID=
OWNER_ID=

DATABASE_URL=

# Optional
LAVALINK_HOST=
LAVALINK_PORT=
LAVALINK_PASSWORD=

OPENAI_API_KEY=
```

### 4. Start the bot

```bash
npm start
```

---

# 📜 Available Scripts

| Command | Description |
| :------ | :---------- |
| `npm start` | Start the bot |
| `npm run check` | Check project for syntax errors |
| `npm run emojis:upload` | Upload application emojis |
| `npm run emojis:dry-run` | Preview emoji upload |

---

# 🛠️ Tech Stack

- Node.js
- discord.js v14
- PostgreSQL
- Sequelize ORM
- Lavalink
- Express
- Canvas

---

# 📁 Project Structure

```text
src/
├── commands/
├── events/
├── handlers/
├── models/
├── services/
├── utils/
└── index.js
```

---

# ❤️ Credits

<div align="center">

<a href="https://discord.com/users/1124248109472550993">
<img src="https://lanyard.cnrad.dev/api/1124248109472550993?bg=1a1b26&idleMessage=Probably%20building%20something..." width="100%">
</a>

## itsfizys

Special thanks for the development and inspiration behind ASTRYX.

</div>

---

# 📄 License

This project is licensed under the **MELON OPEN SOURCE LICENSE**.

See the [LICENSE](./LICENSE) file for complete terms and conditions.

© 2026 **itsfizys (Aegis)**

---

<div align="center">

⭐ If you enjoy this project, consider giving it a star!

Made with ❤️ for Discord communities.

</div>
