<img src="https://files.catbox.moe/c72p4u.png" width="30" style="vertical-align: middle;"> NdiiCia MD WhatsApp Bot

<div align="center">

https://files.catbox.moe/4glouz.png

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.0-blue?style=for-the-badge&logo=github" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=opensourceinitiative" alt="License">
  <img src="https://img.shields.io/badge/Node.js-18+-yellow?style=for-the-badge&logo=nodedotjs" alt="Node.js">
  <img src="https://img.shields.io/badge/Baileys-6.4.0-purple?style=for-the-badge&logo=whatsapp" alt="Baileys">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&width=500&lines=A+Modern+WhatsApp+Bot;Multi+Device+Ready;Feature+Rich+System;Plugin+Based+Architecture" alt="Typing SVG">
</p>

</div>

✨ Fitur Utama

<div align="center">

🚀 📱 🔌 🎨
High Performance Multi-Platform Plugin System Beautiful UI
⚡ Fast response time 📲 All message types 🔧 Easy to extend 🎯 Elegant interface

📸 🛡️ 🔄 💾
Web Screenshot Multi-Owner Auto-Reload Session Mgmt
🖥️ Desktop/Phone/Tablet 👑 Multiple owners 🔁 Live reload 💿 Session storage

</div>

📦 Instalasi & Setup

<details>
<summary><b>🎯 Klik untuk melihat panduan instalasi</b></summary>

Prasyarat

· Node.js v18 atau lebih tinggi
· NPM atau Yarn
· WhatsApp Number

1️⃣ Clone Repository

```bash
# Clone dengan Git
git clone https://github.com/ndiicia/ndicia-md.git
cd ndicia-md

# Atau download ZIP
curl -L https://github.com/ndiicia/ndicia-md/archive/main.zip -o ndicia-md.zip
unzip ndicia-md.zip && cd ndicia-md
```

2️⃣ Install Dependencies

```bash
# Install paket utama
npm install

# Atau dengan Yarn
yarn install
```

3️⃣ Konfigurasi Bot

```javascript
// Edit file config.js
nano config.js  # atau gunakan editor favorit Anda
```

Isi konfigurasi:

```javascript
owner: "6281234567890",  // Nomor WhatsApp Anda
owners: ["6281234567890", "6289876543210"],  // Multi-owner
prefix: ".",  // Prefix command
```

4️⃣ Jalankan Bot

```bash
# Mode production
npm start

# Mode development (auto-restart)
npm run dev

# Debug mode
DEBUG=* node ndicia.js
```

5️⃣ Scan QR Code

```bash
# Setelah menjalankan, scan QR yang muncul
# atau gunakan pairing code
```

</details>

🎮 Command List

<div align="center">

📋 Menu Categories

Category Commands Description
🛠️ Utama .menu, .ping, .owner, .info Basic commands
📸 Media .sticker, .ssweb, .toimg Media processing
👥 Group .tagall, .listadmin, .groupinfo Group management
⚙️ Owner .eval, .exec, .plugins Owner utilities
🔌 Plugin .ai, .weather, .translate Plugin commands

</div>

<details>
<summary><b>📖 Klik untuk melihat detail command</b></summary>

🛠️ Main Commands

```bash
.menu       # Menampilkan semua command
.ping       # Cek kecepatan bot
.owner      # Informasi owner
.info       # Info bot
```

📸 Media Commands

```bash
.sticker    # Buat sticker dari gambar
.ssweb url  # Screenshot website (desktop/mobile/tablet)
.toimg      # Convert sticker ke gambar
```

👥 Group Commands

```bash
.tagall     # Mention semua member
.listadmin  # Daftar admin group
.groupinfo  # Info group
```

⚙️ Owner Commands

```bash
.eval code  # Execute JavaScript
.exec cmd   # Run terminal command
.plugins    # Manage plugins
```

</details>

🔌 Plugin System

<div align="center">

Plugin Examples

```javascript
// plugins/myplugin.js
export default async function(sock, msg, utils) {
    const { args, reply } = utils;
    await reply(`Hello ${args[0]}!`);
}
```

Plugin Commands

```bash
.plugins                # List semua plugin
.plugins load <name>    # Load plugin
.plugins reload <name>  # Reload plugin
.plugins unload <name>  # Unload plugin
```

</div>

📸 SSWeb Feature

<details>
<summary><b>🖼️ Contoh Screenshot Interface</b></summary>

<div align="center">

SSWeb Button Interface

```
📸 SCREENSHOT WEB

URL: https://google.com

Select screenshot type:
┌─────────────────────────────────┐
│  [🌐 Open URL] [🖥️ Desktop]   │
│  [📱 Mobile]   [💻 Tablet]     │
└─────────────────────────────────┘
```

Hasil Screenshot

https://via.placeholder.com/800x400/00ff00/000000?text=Screenshot+Example

</div>

</details>

🏗️ Project Structure

```
ndicia-md/
├── 📁 ndicia.js          # Main bot file
├── 📁 config.js          # Configuration
├── 📁 case.js           # Message handler
├── 📁 package.json      # Dependencies
├── 📁 plugins/          # Plugins folder
│   ├── 📁 ssweb.js     # Screenshot plugin
│   ├── 📁 ai.js        # AI plugin
│   └── 📁 custom.js    # Custom plugins
├── 📁 database/         # Database storage
│   ├── 📁 welcome.json
│   ├── 📁 goodbye.json
│   └── 📁 users.json
└── 📁 ndicia-session/  # Session data
```

🌐 Links & Resources

<div align="center">

Official Links

<p align="center">
  <a href="https://ndiicia.xyz">
    <img src="https://img.shields.io/badge/🌐_ndiicia.xyz-Website-blue?style=for-the-badge&logo=googlechrome" alt="Website">
  </a>
  <a href="https://whatsapp.com/channel/0029Vb69nLG23n3aRi3cpf2U">
    <img src="https://img.shields.io/badge/📢_Channel_Dev-WhatsApp-green?style=for-the-badge&logo=whatsapp" alt="WhatsApp Channel">
  </a>
  <a href="https://github.com/ndiicia">
    <img src="https://img.shields.io/badge/💻_GitHub-Profile-black?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

Support

<p align="center">
  <a href="https://wa.me/6281234567890">
    <img src="https://img.shields.io/badge/💬_Support-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Support">
  </a>
  <a href="https://t.me/ndiicia">
    <img src="https://img.shields.io/badge/📢_Telegram-Channel-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
</p>

</div>

🚀 Quick Start

```bash
# 1. Clone repository
git clone https://github.com/ndiicia/ndicia-md.git
cd ndicia-md

# 2. Install dependencies
npm install

# 3. Configure bot
nano config.js

# 4. Run bot
npm start

# 5. Scan QR code
# 6. Enjoy! 🎉
```

📊 Stats & Analytics

<div align="center">

Metric Status Trend
Uptime 99.8% 📈
Response Time 120ms ⚡
Active Users 500+ 👥
Commands 50+ 🎯

</div>

🤝 Contributing

<div align="center">

<p>Kami menerima kontribusi! Baca <a href="CONTRIBUTING.md">panduan kontribusi</a> untuk memulai.</p>

```bash
# Fork repository
# Buat branch baru
git checkout -b feature/amazing-feature

# Commit changes
git commit -m "Add amazing feature"

# Push ke branch
git push origin feature/amazing-feature

# Buat Pull Request
```

</div>

⚠️ Disclaimer

<div align="center">

Note: This bot is for educational purposes only. Use at your own risk.

· This is not an official WhatsApp product
· WhatsApp is a trademark of Meta Platforms, Inc.
· Follow WhatsApp Terms of Service
· Respect user privacy

</div>

📄 License

<div align="center">

```
MIT License

Copyright (c) 2026 NdiiCia Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONTAINER WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

</div>

🏆 Credits & Thanks

<div align="center">

Development Team

<p align="center">
  <img src="https://files.catbox.moe/g28t9u.png" width="100" alt="NdiiCia Logo">
  <br>
  <strong>NdiiCia Development Team</strong>
  <br>
  <em>Creating amazing bots since 2023</em>
</p>

Special Thanks

· WhatsApp Baileys Library - For the amazing API
· Node.js Community - For excellent tools
· All Contributors - For making this better
· Users - For support and feedback

</div>

⭐ Support Us

<div align="center">

<p>Jika Anda menyukai proyek ini, berikan bintang di GitHub! ⭐</p>

```bash
# Star repository
# Fork project
# Share with friends
# Report issues
# Contribute code
```

Connect With Us

<p align="center">
  <a href="https://ndiicia.xyz">
    <img src="https://img.shields.io/badge/Website-ndiicia.xyz-blue?style=flat-square&logo=google-chrome" alt="Website">
  </a>
  <a href="https://whatsapp.com/channel/0029Vb69nLG23n3aRi3cpf2U">
    <img src="https://img.shields.io/badge/Channel-WhatsApp-green?style=flat-square&logo=whatsapp" alt="WhatsApp Channel">
  </a>
  <a href="https://github.com/ndiicia">
    <img src="https://img.shields.io/badge/GitHub-ndiicia-black?style=flat-square&logo=github" alt="GitHub">
  </a>
</p>

<br>

<h3>🎉 <strong>Powered by NdiiCia © 2026</strong> 🎉</h3>

<p><em>Building the future of WhatsApp automation</em></p>

</div>

---

<div align="center">

🎯 Ready to automate? Start using NdiiCia MD today!

https://img.shields.io/badge/🚀_Deploy_Now-Click_Here-orange?style=for-the-badge&logo=rocket
https://img.shields.io/badge/🎥_Watch_Demo-Video-red?style=for-the-badge&logo=youtube
https://img.shields.io/badge/📚_Full_Documentation-Read-blue?style=for-the-badge&logo=gitbook

</div>
