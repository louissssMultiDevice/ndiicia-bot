

<div align="center">

<!-- LOGO -->
<img src="https://files.catbox.moe/c72p4u.png"
     width="140"
     style="border-radius:50%; border:5px solid #00FFAA; box-shadow:0 0 20px #00ffaa;"
     alt="NdiiCia Logo"/>

<br><br>

<h1>NdiiCia MD</h1>
<h3>⚡ Modern • Secure • Scalable WhatsApp Bot</h3>

<p>
A next-generation <b>Multi-Device WhatsApp Automation System</b>  
built with performance, modularity, and elegance in mind.
</p>

<!-- BANNER -->
<img src="https://files.catbox.moe/4glouz.png"
     width="95%"
     style="max-width:1000px; border-radius:18px; box-shadow:0 20px 40px rgba(0,0,0,.5);"
     alt="NdiiCia Banner"/>

<br><br>

<!-- BADGES -->
<img src="https://img.shields.io/badge/Version-2.0.0-00FFAA?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
<img src="https://img.shields.io/badge/Baileys-6.4.0-25D366?style=for-the-badge&logo=whatsapp"/>
<img src="https://img.shields.io/badge/License-MIT-black?style=for-the-badge"/>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=3000&pause=800&color=00FFAA&center=true&vCenter=true&width=700&lines=Enterprise+Grade+WhatsApp+Bot;Multi+Device+Ready;Plugin+Based+Architecture;Fast+Secure+Reliable"/>

</div>

---

## 🚀 Why NdiiCia MD?

> NdiiCia MD is not just a bot —  
> it is a **WhatsApp Automation Platform**.

<div align="center">

⚡ **Ultra Fast Response**  
🔌 **Dynamic Plugin System**  
📱 **True Multi-Device Support**  
🛡️ **Secure Session Handling**  
🎨 **Clean & Elegant Interface**  
👑 **Multi-Owner Management**

</div>

---

## ✨ Core Features

| Feature | Description |
|------|-------------|
| ⚡ Performance | Optimized async handling & fast execution |
| 🔌 Plugin System | Load / Reload / Unload without restart |
| 📸 Web Screenshot | Desktop / Mobile / Tablet rendering |
| 👥 Group Tools | Admin, tagging, info management |
| 🛡️ Security | Safe eval, owner-only access |
| 🔁 Auto Reload | Development & production ready |

---

## 📦 Installation

<details>
<summary><b>📥 Click to expand installation guide</b></summary>

### Requirements
- Node.js v18+
- NPM or Yarn
- WhatsApp Account

### Clone
```bash
git clone https://github.com/ndiicia/ndicia-md.git
cd ndicia-md

Install

npm install
# or
yarn install

Configuration

// config.js
owner: "628xxxxxxxxxx",
owners: ["628xxxxxxxxxx"],
prefix: ".",

Run

npm start        # Production
npm run dev      # Development
DEBUG=* node ndicia.js

</details>
---

🎮 Command Overview

🧠 Core

.menu      .ping
.owner     .info

📸 Media

.sticker
.ssweb <url>
.toimg

👥 Group

.tagall
.listadmin
.groupinfo

⚙️ Owner

.eval
.exec
.plugins


---

🔌 Plugin Architecture

// plugins/hello.js
export default async (sock, msg, { reply }) => {
  reply("Hello from NdiiCia Plugin 🚀")
}

Manage Plugins

.plugins
.plugins load <name>
.plugins reload <name>
.plugins unload <name>


---

🗂 Project Structure

ndicia-md/
├── ndicia.js          # Main engine
├── config.js          # Configuration
├── case.js            # Message handler
├── plugins/           # Modular plugins
├── database/          # JSON storage
└── ndicia-session/    # Auth sessions
```

🌐 Official Network

<div align="center"><a href="https://ndiicia.xyz">
  <img src="https://img.shields.io/badge/🌐_Website-ndiicia.xyz-0A1AFF?style=for-the-badge&logo=google-chrome"/>
</a><a href="https://whatsapp.com/channel/0029Vb69nLG23n3aRi3cpf2U">
  <img src="https://img.shields.io/badge/📢_WhatsApp_Channel-Join_Community-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a><a href="https://github.com/ndiicia">
  <img src="https://img.shields.io/badge/💻_GitHub-ndiicia-black?style=for-the-badge&logo=github"/>
</a></div>
---

🚀 Get Started Now

<div align="center"><a href="https://github.com/ndiicia/ndicia-md">
  <img src="https://img.shields.io/badge/🚀_Deploy_Now-Start_Building-orange?style=for-the-badge&logo=rocket"/>
</a><a href="https://youtube.com">
  <img src="https://img.shields.io/badge/🎥_Demo-Watch_Video-red?style=for-the-badge&logo=youtube"/>
</a><a href="https://ndiicia.xyz/docs">
  <img src="https://img.shields.io/badge/📚_Docs-Full_Documentation-blue?style=for-the-badge&logo=gitbook"/>
</a></div>
---

⚠️ Disclaimer

This project is for educational purposes only.
Not affiliated with WhatsApp or Meta.


---

📄 License

MIT License © 2026 NdiiCia Team


---

<div align="center"><img src="https://files.catbox.moe/g28t9u.png"
width="120"
style="border-radius:50%; border:4px solid #00FFAA; box-shadow:0 0 15px #00ffaa;"/>

<h3>Powered by NdiiCia © 2026</h3>
<i>Engineering the future of WhatsApp automation</i><br><br>

⭐ If you like this project, give it a star on GitHub!

</div>
