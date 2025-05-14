# MongoDB Backup Bot 📦

A Telegram bot built using [PyTDBot](https://github.com/pytdbot/client) to backup and restore MongoDB databases.


  <!-- Repo Size -->
  <a href="https://github.com/lazzylam/tgmo">
    <img src="https://img.shields.io/github/repo-size/lazzylam/tgmo?style=for-the-badge&color=success" alt="Repo Size"/>
  </a>

  <!-- Language -->
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Written%20in-Python-orange?style=for-the-badge&logo=python" alt="Python"/>
  </a>

- 🔐 Backup MongoDB databases via `/back <URI>`
- 💾 Supports `.gz` (default) and `.json` formats
- 📥 Import backups by replying to a file with `/mongo {import} <URI>`
- 🐳 Docker-ready with pre-installed MongoDB tools
- ⚡ Fully asynchronous and lightweight

## Commands

- `/mongo <mongodb_uri>` — Create a `.gz` backup
- `/mongo {json} <mongodb_uri>` — Create a `.json` backup
- `/mongo {import} <mongodb_uri>` — Restore by replying to a `.gz` or `.json` backup
