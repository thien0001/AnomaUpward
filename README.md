# 🦐 Anoma Upward

![Anoma Upward](static/demo.png)

**Anoma Upward** is a mini-game prototype built with **Godot Engine 4**, inspired by Anoma's "intent-centric" mechanics.

In the game, you control a mage shrimp that flies up with **Upward** energy and demonstrates the power of intent by moving, colliding, and expanding the radius.

Big Intent

---

## ✨ Idea
The game is developed within the framework of **ANOMA INTENTS TUESDAY: REDUX 🔮**, with the goal of:

- 🧙‍♂️ Demonstrate **intent-centric architecture** through gameplay (player → intent → action in the network).

- 🌉 Focus on **multi-chain compatibility**: from Ethereum to many other chains.
- 🎮 Enhance **user experience (UX)** with intuitive UI, fun effects, and dynamic feedback.

- 🪄 Encourage builders to explore how **intents can be visualized and demoed live** through the game.

---

## 🎮 Gameplay

- **Actor Controls:**

- The main character is `Actor.gd`, which inherits from `Area2D`.

- Use `Camera2D` to move the character with the mouse.

- The radius (`radius`) changes based on **mass** and in-game actions.

- **Effects & Feedback:**
- `play_bounce_effect()` → bounce effect when colliding.

- `play_eat_effect()` → light particle effect when absorbing objects.

- Label displays character name + score.

- **Resource:**

- Sprite: `shrimp_circle.png` (shrimp mage image).

- UI: **Anoma Upward** logo, custom background.

-
