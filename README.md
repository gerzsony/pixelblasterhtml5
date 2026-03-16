# PixelBlaster

PixelBlaster is a small browser-based puzzle game where you destroy colored pixels using automatically firing "destroyers".  
The goal is simple: **clear the entire pixel image using as few moves as possible.**

The game runs entirely in the browser and requires **no build tools, dependencies, or installation**.

---

## 🎮 Gameplay

At the top of the screen you see a grid of colored pixels forming an image.

Your task is to destroy every pixel.

### Rules

1. Move **destroyers** from the **storage area** (bottom) to the **active slots** (middle).
2. A destroyer **automatically fires** at pixels of the same color.
3. It always targets the **lowest reachable pixel in a column**.
4. When the bottom pixel of a column is destroyed, the pixel above becomes reachable.
5. Destroyers have **limited ammo**.
6. If a destroyer runs out of ammo or has no valid targets, it disappears.
7. Only the **top row of the storage** can be moved.

The challenge is to choose the right destroyers so you clear the level with **minimum moves**.

---

## ⭐ Scoring

After completing a level, the game evaluates your performance:

- ⭐⭐⭐ Excellent (very few moves)
- ⭐⭐ Good
- ⭐ Completed

The game also stores your **best score per level** locally in the browser.

---

## 🧠 Strategy Tips

- Use destroyers that match **currently reachable colors**.
- Avoid placing destroyers whose color is **blocked above other pixels**.
- Think ahead so you **don't waste ammo**.
- Sometimes clearing a single column opens up multiple new targets.

---

## 🚀 Running the Game

No installation is required.

Simply open the HTML file in any modern browser:

Works in:

- Chrome
- Firefox
- Edge
- Safari
- Mobile browsers

---

## 📁 Project Structure


The entire game is implemented in a **single HTML file** containing:

- HTML structure
- CSS styling
- JavaScript game logic

---

## 💾 Save System

The game stores:

- best scores
- tutorial completion

using **localStorage** in the browser.

No external services or accounts are required.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage API

No frameworks or libraries are used.

---

## 📱 Mobile Friendly

The interface is optimized for:

- touch input
- small screens
- portrait orientation

It behaves like a **mobile web app** when opened on phones.

---

## 📜 License

Free to use and modify.

If you publish a modified version, please keep a reference to the original project.

---

## ✨ Author

Created as a lightweight experimental puzzle game.

Feel free to fork, modify, and improve!

