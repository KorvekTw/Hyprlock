# Hyprlock for Hyprland on Arch Linux

## What is Hyprlock?

**Hyprlock** is a sleek and modern screen locker designed specifically for the [Hyprland](https://github.com/hyprwm/Hyprland) dynamic compositor. It brings both security and style, leveraging the graphical power of Wayland and the flexibility of Hyprland.

---

## Key Features

- 🔒 **Secure and Efficient Locking**: Protect your session quickly and with minimal resource usage.
- 🎨 **Fully Customizable**: Tweak backgrounds, fonts, colors, and widgets to match your setup.
- ⚡ **Native Hyprland Integration**: Runs smoothly and natively, taking advantage of modern Wayland technologies.
- 🖼️ **Image and Effect Support**: Add wallpapers, blur, and transparency for an attractive visual touch.
- 🐧 **Made for Arch Linux (but works on any rolling release distro)**: Easy to install and always up-to-date with the latest packages.

---

## Why Use Hyprlock?

If you want a locker that combines security, aesthetics, and performance, **Hyprlock** is the ideal choice for Hyprland environments. Forget generic lockers and enjoy a consistent and beautiful workflow.

---

## Recommendation

> **Don’t settle for less!** If you use Hyprland on Arch Linux, try Hyprlock and give your workflow a professional, personal touch.  
>  
> ⚙️ *Install it, configure it your way, and you’ll never look back.*

---

## Quick Install

```bash
# On Arch Linux (AUR)
yay -S hyprlock
# Or manually from source
git clone https://github.com/hyprwm/hyprlock.git
cd hyprlock
make && sudo make install
```

---

## Useful Links

- [Official Hyprlock Repository](https://github.com/hyprwm/hyprlock)
- [Hyprland Wiki](https://wiki.hyprland.org/)
- [Arch Linux Community](https://archlinux.org/)

---

Explore, customize, and elevate your Hyprland experience with Hyprlock!

## Getting Started

1. **Add Hyprlock to your Hyprland config:**

   Edit your `~/.config/hypr/hyprland.conf` to set Hyprlock as your screen locker.  
   Example:
   ```ini
   exec-once = hyprlock
   ```

2. **Customize Hyprlock:**

   - Hyprlock can be customized with configuration files for backgrounds, widgets, blur, and more.
   - Refer to the [official documentation](https://github.com/hyprwm/hyprlock#configuration) for advanced options.

3. **Lock your screen:**

   Use your preferred shortcut or command to lock your screen:
   ```bash
   hyprlock
   ```

---

Let me know if you want the next section (like **Configuration**, **Usage**, or **FAQ**) or want to further detail this part!

## Using This Custom Hyprlock Design

This repository contains a custom design and configuration for Hyprlock, curated to provide a unique look and feel to your Hyprland experience on Arch Linux.  
Follow these steps to use **this specific design** from my GitHub repository:

### 1. Clone This Repository

```bash
git clone https://github.com/KorvekTw/hyprlock-custom.git
cd hyprlock-custom
```

### 2. Build and Install

Compile and install Hyprlock with the provided configuration:

```bash
make
sudo make install
```

*Or, if you want to keep your system Hyprlock untouched, you can run it directly from this folder.*

### 3. Copy the Custom Configuration

Copy the provided configuration files and assets (wallpapers, icons, etc.) to your Hyprlock config directory:

```bash
mkdir -p ~/.config/hyprlock
cp -r config/* ~/.config/hyprlock/
```

### 4. Add Hyprlock to Hyprland

Edit your `~/.config/hypr/hyprland.conf` and add (or modify) the following line:

```ini
exec-once = hyprlock
```

### 5. Enjoy Your New Look!

Lock your screen with:

```bash
hyprlock
```

Your custom design should now be active.  
Feel free to tweak the configuration in `~/.config/hyprlock` to better match your style!

---

## Screenshots

Add screenshots here to showcase your design!  
For example:

![screenshot1](screenshots/lockscreen1.png)
![screenshot2](screenshots/lockscreen2.png)

---

## Feedback & Contributions

If you have suggestions or want to contribute new designs, feel free to open an issue or pull request!

---

**Make your Hyprland setup truly yours with this custom Hyprlock design!**
