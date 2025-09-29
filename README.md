# i3-gentoo
> not to be confused with Intel Core i3 Processors.

My personal dotfiles for i3wm.

---

### Programs used
- **Window Manager**: i3wm + picom (for handling vsync)
- **Terminal**: Sakura
- **Application Launcher**: dmenu (default)
- **Text Editor**: VIM (with custom colorscheme)
- **Brightness and Volume Control**: brightnessctl + pulseaudio
- **Image and Video Viewer**: feh (also for background setting) + mpv
- **Screenshot and Screen Recorder**: scrot (short for **SCR**eensh**OT**) + ffmpeg
- **Browser**: Firefox ESR (with userChrome.css for styling)
- **System Status**: Conky

---

## 📂 Repository Structure
```bash
├── chrome
│    └── userChrome.css
├── gtk-3.0
│    ├── gtk.css
│    └── settings.ini
├── i3
│    ├── config
│    └── config.bak
├── picom
│    └── picom.conf
│── sakura
│    └── sakura.conf
└── wallpaper
      └── vim.png
```

## 📝 Notes
- For the terminal, I use MartianMono Nerd Font
- This is a minimal i3 setup. It didn't take me 3 days to fully customize it.
- I mostly use a browser and terminal only, so you may notice there's no fancy file manager, screenshot tool or OBS.
- Even though I do not use a GUI file manager, I still have icon themes, GTK theme and a cursor, mostly for firefox too, and some other occurances if ever.
- I'm still working on this setup, perfect blends of orange, adding more keybinds, more suitable programs, finding a TUI file manager, so on and so forth.

## Sources used/mentioned:
- [Nerd Fonts](https://www.nerdfonts.com/)
- [userChrome.css](https://github.com/Dook97/firefox-qutebrowser-userchrome) for Firefox
- [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) for Icon Theme
- [Skeuos GTK](https://github.com/daniruiz/skeuos-gtk) for GTK Theme, specifically using Orange-Dark variant
