<center>
<h1>SHADB</h1>

A powerful, lightweight, and secure Android system tools app — based on the **Shizuku API**, without the need for full root.
</center>
---

**🔷 WHAT IS SHADB?**

SHADB is an Android administrative app that gives you full control over your device's system — from debloating and freezing apps, changing resolutions, managing permissions, and even using a built-in terminal.

Everything is secure, everything can be rolled back.

---

**📦 COMPLETE FEATURES**

`🗑 Debloater`
Uninstall / disable / hide system & user apps. Supports batch actions + OEM bloatware presets (Samsung, Xiaomi, OPPO, etc.).

`❄️ App Freezer`
Freeze unused apps without deleting data. Instantly save RAM & battery.

`🖥 Display Settings`
Change resolution, DPI, refresh rate, and brightness. Preset HD / FHD / QHD or customize as you like.

`🔐 Permission Manager`
Grant / revoke permissions per-app granularly. See all sensitive permissions each app has.

`🔋 Battery Optimizer`
Force doze, set standby buckets, kill background apps, toggle battery saver — all from one place.

`🌐 Network Tools`
Toggle WiFi, data, airplane mode, flush DNS, set custom DNS, ping tool, per-app network stats.

`⚙️ System Props Editor`
Read and edit all system props (getprop/setprop) by category and search directly from the UI.

`📡 ADB Wireless Manager`
Enable ADB over TCP/IP with one tap and QR code for quick connection.

`📱 Advanced App Manager`
Force stop, clear cache in bulk, backup APKs, launch hidden activities, monitor running processes and services.

`🔊 Volume & Audio`
Control all audio streams (media, ring, notification, alarm, call) via sliders.

`💾 Rollback Center`
**All actions are saved.** At any time, undo one action or roll back all at once to the original state.

`>_ Built-in Terminal`
Run shell commands manually via Shizuku. There's a command history and syntax highlighting output.

- Any Freature In App

---

**🛡 WHY IS IT SAFE?**

✅ All commands run via **Shizuku IPC** — not Runtime.exec() directly
✅ **Room DB-based rollback system** — all actions are reversible
✅ Mandatory confirmation before destructive actions
✅ **Self-protect** — the SHADB package itself cannot be deleted from within the app
✅ Whitelist system-critical packages (SystemUI, Phone, etc.)
✅ Log all actions with timestamps

---

**📋 REQUIREMENTS**

```
Android: 10+ (API 29)
Shizuku: Must be enabled (via ADB / Wireless ADB)
Root: NOT required
```

> 💡 Shizuku can be enabled without root via ADB only once.
> Download Shizuku: [Play Store](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api)

---

**⚙️ TECH STACK**

```
Language : Kotlin + Jetpack Compose
Architecture: MVVM + Clean Architecture
AT: Hilt
Database : Room (rollback engine)
API : Shizuku 13.1.5
UI : Material Design 3 — Dark Theme
```

---


*Feedback, bug reports, and feature suggestions? Drop them in the reply section or DM us directly.*
*Start ⭐ if helpful!*