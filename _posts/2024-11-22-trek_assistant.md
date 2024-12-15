---
title: "Trek Assistant"
image: "/assets/img/screenshots/trek_assistant/ta_main.jpg"
subtitle: "Home assistant system project"
date: 2024-11-22
categories: [Blog]
tags: [Home Assistant, Android, AI, Data, Automation]
comments: true
---

Here is the first post about my home assistant system project *Trek Assistant*: A feature list and screenshots of the four Android app views with their descriptions and of the server console. More details might follow in the future.

## Features

This is a partial overview of the app's functionalities:

- Text-to-Speech (TTS) via gTTS
- Server control (restart, stop)
- Screenshot
- Timer (create, list, stop)
- GPT-Chat
- Auto shutdown
- Weather report
- Process Management (list, search)
- Close programs
- Reminder (set, cancel, list)
- File search
- Play sounds
- Run shell commands
- Wake-on-LAN (including a placeable widget for the home screen)
- Voice commands
- Pomodoro sessions
- Execute scripts
- Play joke
- Take video
- Take photo
- Media controls (play/pause, next, previous)
- Volume control
- Start browser
- Google maps search
- Google search
- Remote PC key input
- Open URL (specific websites)
- Remote PC power management (power off, reboot, hibernate)
- Display quotes
- various gimmicks


## Views

There are four different views: *Main*, *Console*, *Log* and *Settings*.

![Main](/assets/img/screenshots/trek_assistant/ta_main.jpg)

This is the preset view, that is initially displayed when the app is started. This is primarily intended to convey a certain look and feel. Furthermore, some gimmicks are built in here, that are not included in the feature list. However, some functions such as WOL or remote shutdown are included here. The view displayed first can be customized in the settings.

![Console](/assets/img/screenshots/trek_assistant/ta_console.jpg)

The console shows various functions for quick selection:

- Free command input
- Switch through the command history
- timer
- Reminder
- Volume control
- Node control
- Media control
- Text-to-speech
- Camera stream and quick shot

![Log](/assets/img/screenshots/trek_assistant/ta_log.jpg)

The log view shows entered commands and their returns as well as status changes of the connected nodes.

![SharedPreferences](/assets/img/screenshots/trek_assistant/ta_prefs.jpg)

The settings (SharedPreferences) include the numerous customization options of the application.

![Server: Console](/assets/img/screenshots/trek_assistant/ta_server.png)

The server console displays status information, configurations, e.g. for auto-shutdown, mode (IPv4/IPv6) and received inputs and responses. As an alternative to the app, commands can also be executed directly via prompt.
