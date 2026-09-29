# CaptainGame

<p align="center">
  <b>A simple interactive treasure-hunting Android game built with Kotlin and Jetpack Compose.</b>
</p>

<p align="center">
  <a href="https://github.com/s-modak09/CaptainGame/releases/tag/v1.0.0">
    <img src="https://img.shields.io/badge/Download-v1.0.0-2ea44f?style=for-the-badge&logo=android" alt="Download">
  </a>
</p>

---

## About

CaptainGame is a simple interactive Android game where the player takes the role of a captain navigating in different directions in search of hidden treasure.

The player can choose to sail **East, West, North, or South**. After each decision, the game randomly determines whether the player discovers a treasure or encounters a storm.

The game keeps track of the number of treasures found and displays the current sailing direction and game status.

This project demonstrates the implementation of interactive game logic, state management, random events, and user interaction using Kotlin and Jetpack Compose.

---

## Gameplay

The player can choose one of four sailing directions:

- Sail East
- Sail West
- Sail North
- Sail South

After selecting a direction, the game randomly determines the outcome.

### Possible Outcomes

**Treasure Found**

The treasure counter increases and the game displays a successful treasure discovery.

**Storm Ahead**

The game displays a storm message and the treasure counter remains unchanged.

The player can continue selecting different directions to search for more treasure.

---

## Features

- Interactive sailing controls
- Four navigation directions
- Random treasure discovery
- Random storm events
- Treasure counter
- Current direction display
- Game status display
- Simple and responsive user interface
- Jetpack Compose-based UI
- Kotlin-based game logic

---

## Download

### Version 1.0.0

Download and install the latest release of CaptainGame from GitHub.

**[Download CaptainGame v1.0.0](https://github.com/s-modak09/CaptainGame/releases/tag/v1.0.0)**

Open the release page and download the required APK from the **Assets** section.

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **Kotlin** | Primary programming language |
| **Jetpack Compose** | Declarative UI development |
| **Material 3** | UI components and design |
| **Android Studio** | Development environment |
| **Gradle** | Build and dependency management |
| **Git & GitHub** | Version control |

---

## Game Logic

The game uses Kotlin's random number generation to determine the result of each sailing action.

The basic gameplay logic is:

```text
Player selects a direction
          |
          v
   Random event occurs
          |
     +----+----+
     |         |
     v         v
  Treasure    Storm
     |         |
     v         v
Counter +1   Display warning
