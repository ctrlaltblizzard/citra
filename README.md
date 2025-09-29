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
├── conky
│    └── conky.conf
├── fastfetch
│    └── config.jsonc
├── gtk-3.0
│    └── gtk.css
├── i3
│    └── config
├── picom
│    └── picom.conf
└── wallpaper
      └── cow.png
      └── vim.png
README.md
```

## 📝 Notes
- This is configured on 1366x768 resolution.
- Conky is a bit of a mess to configure, especially that it works weird with scrot when doing an area screenshot.
- For the terminal font, I am using [Martian Mono Nerd Font.](https://www.programmingfonts.org/#martian-mono)
- I did not include `.vimrc` since I am still working on the configurations of it.
- Package `brightnessctl` is in the [GURU](https://gpo.zugaina.org/app-misc/brightnessctl) overlay, if you want to install it, enable [GURU.](https://wiki.gentoo.org/wiki/Project:GURU)
- Configurations on Gentoo and other distributions are a little different, with a little tweaking on the configuration files it should work.

## Sources used/mentioned:
- [Nerd Fonts](https://www.nerdfonts.com/)
- [userChrome.css](https://github.com/Dook97/firefox-qutebrowser-userchrome) for Firefox, added/changed extra configurations for my personal use.
- [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) for Icon Theme
- [Skeuos GTK](https://github.com/daniruiz/skeuos-gtk) for GTK Theme, specifically using Violet-Dark variant
- [Conky Config](https://github.com/davilatwin/conky_theme) for reference, but I changed some configurations for my personal use.
