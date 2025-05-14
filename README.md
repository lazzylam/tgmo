# MongoDB Backup Bot 📦

ʙᴏᴛ Tᴇʟᴇɢʀᴀᴍ ʏᴀɴɢ ᴅɪʙᴜᴀᴛ ᴍᴇɴɢɢᴜɴᴀᴋᴀɴ [PyTDBot](https://github.com/pytdbot/client) ᴜɴᴛᴜᴋ ᴍᴇɴᴄᴀᴅᴀɴɢᴋᴀɴ ᴅᴀɴ ᴍᴇᴍᴜʟɪʜᴋᴀɴ ᴅᴀᴛᴀʙᴀsᴇ MᴏɴɢᴏDB.


  <!-- Repo Size -->
  <a href="https://github.com/lazzylam/tgmo">
    <img src="https://img.shields.io/github/repo-size/lazzylam/tgmo?style=for-the-badge&color=success" alt="Repo Size"/>
  </a>

  <!-- Language -->
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Written%20in-Python-orange?style=for-the-badge&logo=python" alt="Python"/>
  </a>

- 🔐 Backup MongoDB database via `/back <URI>`
- 💾 support `.gz` (default) and `.json` formats
- 📥 mencadangkan database dengan membalas file menggunakan `/back {import} <URI>`
- 🐳 Docker-ready with pre-installed MongoDB tools
- ⚡ Full async dan sangat ringan

## Commands

- `/mongo <mongodb_uri>` — Create a `.gz` backup
- `/mongo {json} <mongodb_uri>` — Create a `.json` backup
- `/mongo {import} <mongodb_uri>` — Restore by replying to a `.gz` or `.json` backup
