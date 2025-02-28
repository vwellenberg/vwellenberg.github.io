---
title: "RocketChat-WhatsApp-Client (2014)"
image: "/assets/img/screenshots/rocketchat/RocketChat_online.jpg"
subtitle: "RocketChat"
date: 2025-02-28
categories: [Blog]
tags: [Android, RocketChat, WhatsApp, Signal, Chat, Backend, Desktop, Mobile, Frontend, UI, UX]
comments: true
---

## 🚀 RocketChat – My little WhatsApp alternative from back in the days

**RocketChat** was created in late 2014 to comfortably send messages directly from your desktop PC – roughly one and a half years before WhatsApp officially introduced their own desktop client on May 10, 2016.

### 📱 How RocketChat worked

The principle was designed to be straightforward:

- **Server (Android app)**: You launch the app on your Android smartphone, which listens for incoming connections.
- **Client (Desktop, Java, Swing)**: The desktop client automatically scans your local network and connects to the smartphone server. Should the automatic search fail, you could simply enter the displayed IP address manually on the smartphone to establish a connection.

When connected successfully, a minimalist chat window opens on the desktop, allowing direct text input. After sending a message from your desktop, a selection pops up on your smartphone, letting you transparently choose the messenger app and recipient to forward the message via Android intents.

### 🖥️ Implementation & Features

- 🔄 Automatic client/server discovery via local network.
- 📋 Manual IP fallback option provided.
- 🔔 Adjustable settings: auto-start, sounds, vibration, and pop-up message previews on Android.

- 📦 Minimalist and lightweight desktop client built with Java and Swing.

- 📨 Message dispatching through various installed messenger apps via Android intents.
- 🎨 Customizable look and feel (multiple designs available)

### ⏳ Fun side note

At the time, there wasn't an official WhatsApp desktop client. Ironically, shortly after RocketChat’s development, WhatsApp released their own official solution, resulting in RocketChat never being widely distributed. However, a couple of friends tested and enjoyed RocketChat extensively, some even using it regularly for quite a while.

### 🎞 Screenshots

![Android Server App: Start screen (connected)](/assets/img/screenshots/rocketchat/RocketChat_online.jpg)

**Android server app**: Displays your connection IP address and input for targeted phone numbers.

![Java desktop chat client](/assets/img/screenshots/rocketchat/RocketChat_DesktopClient.png)

**Java desktop chat client**: Clean user interface, straightforward chatting experience.

![Settings screen](/assets/img/screenshots/rocketchat/RocketChat_SharedPrefs.jpg)

**Settings screen**: Clearly-arranged menu allowing individual customization of the Android app.

A small but delightful project looking back—definitely worth a bit of nostalgic appreciation 🚀
