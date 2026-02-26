# Ao Oni - Password Trainer

A high-performance web-based training tool designed for the **Ao Oni speedrunning community**. Practice complex password sequences with frame-perfect feedback, smart notation hints, and authentic audio cues.

**Created by :** Adel'gid Aragami (creator of the [MASTER library](https://github.com/Adel-gid/MASTER))

## 🚀 Features

* **Smart Notation Algorithm :** Automatically calculates the shortest input sequence (Up/Down/Left/Right/Z) for any code using a custom JavaScript implementation of the optimal path algorithm.
* **Authentic Feel :** Mimics the input delay and UI behavior of the original *Ao Oni* (RPG Maker XP/VX era).
* **Dynamic Configuration :**
  * **All Mode :** Practice every variation in a sequence.
  * **Random Mode :** Practice a single randomized valid code from a set.
  * **Custom Sections :** Add, rename, or delete your own password categories and codes.
* **Pro-Trainer Features :**
  * **Blind Mode :** Hold `Q` while clicking "Full Restart" to hide digits (practice by muscle memory only).
  * **Mute Toggle :** Quickly enable/disable audio.
  * **Detailed Timer :** Track your speed down to the millisecond.

## 🎧 Audio Setup (Important)

Due to licensing restrictions, the original audio files from **RPG Maker VX Ace RTP** are **not included** in this repository. 

To enable the authentic sound effects, you must manually place the following files into an `Audio/` folder in the root directory :

1. `001-System01.ogg` (Move/Select)
2. `002-System02.ogg` (Confirm/Start)
3. `003-System03.ogg` (Cancel/Restart)
4. `004-System04.ogg` (Error/Unavailable)

### Where to find these sounds :
* **Official RTP :** Download the [RPG Maker VX Ace RTP](https://www.rpgmakerweb.com/run-time-package).
* **Ao Oni Wiki :** Individual sound files can be found on the [Ao Oni Fandom Sound Gallery](https://aooni.fandom.com/wiki/Sound).

## 🛠 Installation

1. Download `index.html`.
2. Create a folder named `Audio` in the same directory.
3. Place the `.ogg` files mentioned above into the `Audio` folder.
4. Open `index.html` in any modern web browser.

## ⚖️ License

### Code
The source code (`index.html`) is licensed under the **BSD 2-Clause "Simplified" License**. See the `LICENSE` file for details.

### Assets & Trademarks
* **Ao Oni** is a game developed by noprops. This tool is an unofficial fan project.
* **RPG Maker VX Ace RTP** materials are the property of **KADOKAWA / ENTERBRAIN, INC.** Their use is governed by their own EULA (see `LICENSE_RTP.txt`). This project does not distribute these assets.