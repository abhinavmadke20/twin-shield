# 🎮 Twin Shield

A fast-paced **2-player retro defense game** built using **HTML, CSS, and JavaScript (Canvas API)** with neon CRT effects, XP upgrades, shields, and audio support.

---

## 🚀 Features

* **Two Players**

  * Player 1: `[A][D]` to move, `[W]` to shoot
  * Player 2: `[←][→]` to move, `[↑]` to shoot

* **Gameplay Mechanics**

  * Enemies spawn faster over time.
  * Collect **XP** to level up.
  * Upgrade to a **shield** by sacrificing Player 2.
  * Shield absorbs damage but has limited health & time.
  * Restore Player 2 when shield expires or breaks.

* **Retro Styling**

  * CRT scanlines & glow effects.
  * Neon-styled UI with XP bars, hearts, and shield health.
  * Glowing feedback messages (e.g., “🛡️ SHIELD ACTIVATED!”).

* **Audio System**

  * Background looped audio (`assets/audio.wav`).
  * Toggle sound with `[M]`.

* **Game States**

  * Upgrade modal after 20 seconds.
  * Sacrifice dialog for Player 2.
  * Game over screen with `[R]` restart option.

---

## 🕹️ Controls

* Player 1:

  * `A` / `D` → Move left/right
  * `W` → Shoot

* Player 2:

  * `←` / `→` → Move left/right
  * `↑` → Shoot

* Other Keys:

  * `M` → Toggle audio
  * `R` → Restart game

---

## 📂 Project Structure

```
Retro-Defense-Game/
│── index.html        # Main game file (HTML, CSS, JS in one file)
│── assets/
│   └── audio.wav     # Background soundtrack
│── README.md         # Project documentation
```

---

## 🛠️ How to Run

1. Clone or download this repository:

   ```bash
   git clone https://github.com/yourusername/retro-defense-game.git
   cd retro-defense-game
   ```

2. Open `index.html` in your browser.

   * Works best on **Chrome / Edge / Firefox**.
   * Make sure `assets/audio.wav` is present for background music.

3. Play with a friend and defend against enemies! ⚡

---

## 📸 Screenshots

*(Add screenshots/GIFs of gameplay here if possible)*

---

## 📜 License

This project is open-source under the **MIT License**.
Feel free to fork, modify, and share!

---

💡 *Tip: Try surviving long enough to see the sacrifice & shield mechanics in action!* ⚡
