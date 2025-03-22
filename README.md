# 🚀 Rofi Configuration  

Rofi is a powerful application launcher and window switcher. This configuration enhances its aesthetics and usability with a sleek theme and custom keybindings.

---

## 📜 Installation  

1. **Install Rofi** (if not already installed):  
   ```sh
   yay pacman -S rofi
   ```

2. **Copy the configuration file** to the appropriate directory:  
   ```sh
   git clone git@github.com:WhoisCipher/rofi-config.git
   mkdir -p ~/.config/rofi
   cp config.rasi spotlight-dark.rasi ~/.config/rofi/config.rasi
   ```

3. **(Optional) Copy the theme file** if using a custom theme:  
   ```sh
   cp theme.rasi ~/.config/rofi/theme.rasi
   ```

---

## 🎨 Features  

✅ **Minimal & Elegant UI** – Aesthetic and clean theme.  
✅ **Keybindings** – Easy navigation and quick access to applications.  
✅ **Fast & Lightweight** – Optimized for speed and efficiency.  
✅ **Drun Mode Enabled** – Quickly launch installed applications.  
✅ **Window Switching** – Easily switch between open windows.  

---

## 🔧 Usage  

- **Run Rofi as an application launcher**:  
  ```sh
  rofi -show drun
  ```
- **Run Rofi as a window switcher**:  
  ```sh
  rofi -show window
  ```
- **Use custom theme** (if available):  
  ```sh
  rofi -show drun -theme ~/.config/rofi/theme.rasi
  ```

---

## ⚙️ Customization  

Modify `config.rasi` to tweak the UI, fonts, colors, and animations.  
To edit, open the file in your favorite editor:  
```sh
nvim ~/.config/rofi/config.rasi
```

---

## 📌 Notes  

- Ensure you have a proper font installed (e.g., `JetBrains Mono`, `Hack`, `Fira Code`).
- If Rofi does not appear properly, try running:  
  ```sh
  rofi-theme-selector
  ```

---
