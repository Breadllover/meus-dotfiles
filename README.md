# 💜 Retro Violet Evangelion Rice

### Details:
- **WM:** Hyprland
- **Bar:** Waybar (Fixed 1600px)
- **Browser:** Zen Browser (Main) & Firefox
- **Notifications:** SwayNC
- **Launcher:** Rofi
- **Terminal:** Kitty & Alacritty (Retro TV)
- **Shell:** Zsh (Oh-My-Zsh)
- **File Manager:** Yazi & Dolphin
- **Fonts:** Nerd Fonts
- **System Monitor:** btop

---

## 🚀 Installation Guide

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Breadllover/meus-dotfiles.git ~/meus-dotfiles
   ```

2. **Install dependencies (Arch Linux):**
   ```bash
   sudo pacman -S hyprland waybar kitty rofi swannc wlogout dolphin zsh
   ```

3. **Apply configurations:**
   ```bash
   # Create config folders if they don't exist
   mkdir -p ~/.config/hypr ~/.config/waybar
   
   # Copy files
   cp -r ~/meus-dotfiles/hypr/* ~/.config/hypr/
   cp -r ~/meus-dotfiles/waybar/* ~/.config/waybar/
   ```
