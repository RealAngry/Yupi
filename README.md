# 📘 Yupi Bot – Documentation  
> The most advanced staff management bot for Discord – made for moderation professionals.

---

## 🚀 Overview

**Yupi** is a feature-rich Discord bot designed to automate staff workflows for professional Discord communities.  
From **role-based promotions** and **strike systems** to **leave applications** and **performance analytics**, Yupi ensures your staff team stays organized, efficient, and accountable.

> 🔄 **Status:** Actively deployed in `97+ servers` with real-time message tracking, performance monitoring, and analytics dashboards.

---

## 🧠 Tech Stack

| Component        | Description                                      |
|------------------|--------------------------------------------------|
| **Discord.js**   | v14.15.3 – Full support for slash + prefix cmds  |
| **Node.js**      | Runtime environment                              |
| **MongoDB Atlas**| Cloud DB with schema via Mongoose                |
| **Node-cron**    | Scheduled tasks for resets and inactivity checks |
| **Winston**      | Production-level logging                         |

---

## 📌 Key Features

✅ Staff Role Management – Promotion & Demotion  
✅ Configurable Strike System – Auto-warnings with limits  
✅ Leave Applications – Approval UI via buttons + modals  
✅ Real-Time Message Tracking – Daily/weekly/monthly activity  
✅ Advanced Profile Views – Weekly goals, performance scores  
✅ Staff Dashboard – Full performance, activity, and strike overview  
✅ Analytics – View server health and moderation efficiency  
✅ Emoji Customization – Use your own emojis for embeds/UI  
✅ Interactive Setup – Modals, dropdowns, and buttons

---

## 🔄 Recent Changes (July 2025)

- ✅ Prefix support added: All commands now work with both `/slash` and `!prefix`
- ✅ `/setup` enhancements: Custom prefix, timezone, and module toggles
- ✅ `/help`: Complete dynamic help command with custom emojis
- ✅ `/viewprofile`: Shows real-time stats, goal progress, and activity
- ✅ `/staffdashboard`: One-page hub for all staff metrics
- ✅ `/activity` + `/performance`: Full activity and scoring with multiple views

---

## 🧾 Commands

All commands are available with both slash (`/`) and prefix (`!`) usage:

- `/setup` / `!setup` – Interactive server configuration  
- `/staff` / `!staff` – Add/remove staff members  
- `/promote` / `!promote` – Promote staff  
- `/demote` / `!demote` – Demote staff  
- `/strike` / `!strike` – Issue/remove strikes  
- `/leave` / `!leave` – Apply for leave  
- `/leaves` / `!leaves` – Review/manage leave requests  
- `/viewprofile` / `!viewprofile` – View detailed staff profile  
- `/statistics` / `!statistics` – Server moderation analytics  
- `/staffdashboard` / `!staffdashboard` – All-in-one staff hub  
- `/activity` / `!activity` – Track staff messages & consistency  
- `/performance` / `!performance` – Scoring and improvement insights  
- `/help` / `!help` – Complete help command with custom emojis

---

## ⚙️ Preferences

- Communication: Clear, professional, and minimal
- Architecture: Modular with strong error handling
- Deployment: Default platform is **Replit**
- Focus: Stability and performance > flashy features

---

## 🧱 Project Structure

📁 commands/ # All slash & prefix command files
📁 events/ # Event listeners (ready, message, interaction)
📁 models/ # MongoDB schemas (Staff, Leaves, Strikes, etc.)
📁 utils/ # Utilities (logger, emojis, validators, etc.)
📁 logs/ # Daily rotating logs via Winston


---

## 📊 Real-Time Bot Stats API

> Coming Soon: `/api/stats` – Pulls live server count, uptime, users, and command usage.

---

## 👑 Author

- Made with ❤️ by **Angry**
- GitHub: `https://github.com/RealAngry`
- Invite Yupi: `https://discord.com/oauth2/authorize?client_id=1348595265346732033`
- Support: `[https://discord.gg/YOURSUPPORT](https://discord.gg/BuS4ZpTpfu)`

EOF
