# Hi, I'm Yusuf 👋

Computer Engineer and Android developer building native apps with **Kotlin** and **Jetpack Compose**. I like small, polished apps that work offline and don't ask for an account.

## Projects

| Project | What it does | Built with | Checks |
|---|---|---|---|
| [**Kilo Takibi**](https://github.com/cusufcan/kilo-takibi-android)<br>[Google Play](https://play.google.com/store/apps/details?id=com.yusufcanmercan.weight_track_app) | Weight tracker with a smoothed trend, date-based chart, goal, reminder, widget and CSV import/export. Entries are stored on the device. | Compose, Room, Flow, Hilt, DataStore | [![CI](https://github.com/cusufcan/kilo-takibi-android/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/cusufcan/kilo-takibi-android/actions/workflows/ci.yml)<br>Unit and device tests |
| [**TOGÜ Yemekhane**](https://github.com/cusufcan/togu-yemekhane-android)<br>[Google Play](https://play.google.com/store/apps/details?id=com.mercan.app) | Unofficial university cafeteria menu. Instead of a server, a scheduled Kotlin job publishes the menu as static JSON; the app keeps it on the device and works offline. | Compose, Room, Flow, Hilt, Jsoup, GitHub Actions | [![CI](https://github.com/cusufcan/togu-yemekhane-android/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/cusufcan/togu-yemekhane-android/actions/workflows/ci.yml)<br>Unit tests |

## How I work

- **Design first.** Scope and screen mockups come before code.
- **Decisions with reasons.** I record each technical decision and why I made it.
- **Clear data flow.** MVVM with unidirectional data flow, with Room as the source for stored data.
- **Small steps.** One change per commit; CI runs tests, lint and a build.
- **Two languages.** Every app ships in English and Turkish, in light and dark theme.

## How I use AI

I build in collaboration with AI coding agents such as Claude and Codex, and both projects above say so in their READMEs. Scope, design and architecture decisions are mine, and I don't move on to the next task until I understand the change.

## Stack

**Android:** Kotlin · Jetpack Compose · Room · Hilt · Coroutines & Flow · DataStore · JUnit

**General:** Firebase · Git · GitHub Actions
