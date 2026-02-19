# 🎮 Tic Tac Toe - Advanced Flutter Edition

A sophisticated Tic Tac Toe application built with Flutter, focusing on high-quality UI/UX, seamless transitions, and interactive animations. This project demonstrates the implementation of complex game logic combined with a polished, responsive interface.

---

## 🚀 Key Features

* **Smart Game Logic**: Full implementation of Tic Tac Toe rules, including win detection (horizontal, vertical, diagonal), draw handling, and score tracking for Player X and Player O.
* **Dynamic Theming**: Integrated Light and Dark mode support that adapts the entire UI color palette, including gradients, glows, and shadows.
* **Interactive Cards**: 
    * **Tactile Feedback**: Player cards and game tiles feature interactive animations using `AnimatedContainer` and `Tween` to provide a "pop" effect on tap.
    * **State Awareness**: Cards visually reflect the current turn and winner status through dynamic borders and scaling.
* **Win Celebration**: A dedicated interactive animation triggers upon victory, highlighting the winning combination with a unique visual sequence to celebrate the player's achievement.
* **Full Localization**: Support for English (LTR) and Arabic (RTL) layouts with automatic UI mirroring.

---

## 🛠 Technical Stack & Core Concepts

This project serves as a practical application of the following Flutter concepts:

### 1. Animations (The Heart of the UI)
* **Implicit Animations**: Used for smooth transitions between theme changes and card state updates using `AnimatedOpacity`, `AnimatedScale`, and `AnimatedPadding`.
* **Explicit Animations**: Implementation of `AnimationController` and `CurvedAnimation` for the winning sequence and custom gestures.
* **Visual Feedback**: Utilizing `Tween` animations to create scaling effects when a player marks a cell.

### 2. UI/UX & Theming
* **Responsive Layout**: Built to look great on various screen sizes using `LayoutBuilder`.
* **Theming Engine**: Deep integration of `ThemeData` to switch between a vibrant Dark Mode and a clean Light Mode.

### 3. State Management
* Efficiently managing the game board state, turn switching, and real-time score updates.

---

## 📸 Project Preview

| Feature | Preview |
| :--- | :--- |
| **Dark Mode & Win State** | *[Insert GIF/Image Here]* |
| **Light Mode ** | *[Insert GIF/Image Here]* |
| **Interactive Card Clicked ** |  |

---

## ⚙️ Getting Started

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/tic-tac-toe-flutter.git](https://github.com/your-username/tic-tac-toe-flutter.git)
    ```
2.  **Install dependencies**:
    ```bash
    flutter pub get
    ```
3.  **Run the app**:
    ```bash
    flutter run
    ```

---

## 🎯 Learning Path
This project fulfills the requirements of mastering **Core Animation Types** and **Theming**, serving as a stepping stone toward building a full **Animated Onboarding Experience**.

---

**Next Step:** Would you like me to provide the code snippet for the **Win Celebration** animation using `AnimationController`?
