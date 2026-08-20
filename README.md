# 📋 ZOE Clipboard Book

ZOE Clipboard Book is an advanced clipboard manager that works like a notebook library.  
Use it for coding, typing, or even inside games – **it works in fullscreen mode**.

Tested on deep system layers and fullscreen applications, including TLauncher and Minecraft.

---

## ✨ Features
- Floating menu with `Ctrl+Shift+Z`
- Save notes in categorized notebooks
- Quick copy to clipboard
- **Works in fullscreen games** (TLauncher, Minecraft, etc.)
- Keyboard navigation: `↑↓` to move, `Enter` to copy, `Esc` to close

---

## ⚠️ Deep-Layer Trick for TLauncher (if needed)

ZOE works in fullscreen mode by default.  
However, if you ever need to push it to an even deeper layer (above the launcher and the game itself), follow this trick:

1. Press **`F11`** once (switch to windowed mode).
2. Press **`Alt + Enter`**.
3. Press **`F11`** again.
4. Now press **`Ctrl + Shift + Z`** to open the floating menu.

This places ZOE **above TLauncher and even above Minecraft itself** – in the deepest visible layer possible.

> 💡 This trick forces the overlay into a higher-priority system layer.

---

## 🚀 How to Use
1. Run `ZOE_Clipboard_X10.exe`
2. Press `Ctrl+Shift+Z` to open the floating menu
3. Navigate with arrow keys, copy with `Enter`

---

## 🛠️ Technologies Used
- Python + Tkinter
- WinAPI for topmost overlay
- Admin rights for deep system layer access
