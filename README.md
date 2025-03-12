<div align="center">
  <img src="https://github.com/sxyazi/yazi/blob/main/assets/logo.png?raw=true" alt="Yazi logo" width="20%">
</div>

<h3 align="center">
	Aurora Storm Flavor for <a href="https://github.com/sxyazi/yazi">Yazi</a>
</h3>

## 👀 Preview

<img src="preview.png" width="600" />

## ✨ Features

- **Deep Twilight Backgrounds:** Uses a rich, cool-toned dark base (`#161920`, `#1a1b2c`) that is easy on the eyes for late-night coding sessions.
- **Aurora-Inspired Accents:** Vibrant but soothing highlight colors including glowing teals, soft roses, and luminous ambers.
- **Crisp Readability:** Soft ice-blue foreground text (`#c8d0ea`) ensures excellent contrast without the harshness of pure white.
- **Powerline Ready:** Beautifully styled status bar and tabs with built-in powerline separator support.
- **Custom Filetype & Icon Colors:** Intuitive color-coding for different file types and directories to help you navigate at a glance.

## 🎨 Installation

### Using package manager

```bash
ya pkg add kshakwat/aurora-storm
```

### Manual install

```bash
# Linux/macOS
git clone https://github.com/kshakwat/yazi-theme/aurora-storm.yazi.git ~/.config/yazi/flavors/aurora-storm.yazi

# Windows
git clone https://github.com/kshakwat/yazi-theme/aurora-storm.yazi.git %AppData%\yazi\config\flavors\aurora-storm.yazi
```

## ⚙️ Usage

Add the these lines to your `theme.toml` configuration file to use it:


```toml
[flavor]
use = "aurora-storm"
# For Yazi 0.4 and above
# switch between light and dark automatically based on terminal settings
dark = "aurora-storm"
light = "aurora-dawn"
```

## ⚙️ Requirements

- [Yazi](https://github.com/sxyazi/yazi) v0.4 or higher.
- A terminal emulator that supports true color (24-bit).
- A Nerd Font installed and configured in your terminal (for the icons).

## 💡 See Also

Prefer a lighter look? Check out the daytime version: **[Aurora Dawn](https://github.com/kshawkat/aurora-dawn)**!

## 🤝 Contributing

Pull requests and suggestions are welcome! If you find a UI element that lacks styling or have ideas to improve the color balance, feel free to open an issue.

## 📜 License

The flavor is MIT-licensed, and the included tmTheme is also MIT-licensed.

Check the [LICENSE](LICENSE) and [LICENSE-tmtheme](LICENSE-tmtheme) file for more details.
