# Tsukiyomi

An elegant AwesomeWM configuration focused on beauty. Comes with a carefully crafted UI, three colorschemes, and a couple of variables to tweak the interface to the user's likings. A WIP currently. You can see this repo as a hybrid between dotfiles and an AWM configuration, but it should be modular enough to only pick what you really plan to use.

> __WARNING__: This configuration was not tested on other machines or OS's outside of mine, my code is also not perfect, since this is my first real attempt at AWM, the code may or may not work on your end, some things here need manual tweaking and errors may occur, procceed at your own caution, you've been warned.

---

### Dependencies

#### Awesome-related, obligatory
- [awesome-git](https://github.com/awesomeWM/awesome)
- [rubato](https://github.com/andOrlando/rubato) (animations library)
- [bling](https://blingcorp.github.io/bling/) (scratchpads and launcher)

> __WARNING 2:__ As of November 6 2023 you need to manually build awesome from source with [this patch](https://github.com/awesomeWM/awesome/pull/3811) for this configuration to work, this is because of a small screen signal for properly setting wallpapers, everything else can be used as is

#### Music related, optional
- `mpd`
- `playerctl`
- `mpDris2`
- `ncmpcpp`
- [`clematis`](https://github.com/TorchedSammy/clematis/tree/host-album-art)

#### Misc Software
- `picom` (optional)
- `bluez` (optional)
- `maim`, `xclip`, `slop` (obligatory)
- `IBM Plex Sans` (optional) and/or any [Nerd Font](https://www.nerdfonts.com/)
- `Pipewire` and `Wireplumber` (obligatory)
- `nemo` (optional)

Your suite of apps can be swapped out with relative ease, but if you want to use exactly what i have, [siduck's build of st](https://github.com/siduck/st), [my custom neovim configuration](https://github.com/tsukki9696/totsuka) and firefox.

---

### Features

Tsukiyomi has a powerful user configuration in which you can tweak things like:
- Colorscheme
- Suite of apps
- Font and icon theme
- UI elements (gaps, spacing, borders)
- Toggleable UI elements and signals
- Accent color
- Layouts and tags
- Wallpaper, avatar, home icon
- Dock widget
- Vertical bar
- Titlebars
- Modkeys

And other aspects can also be tweaked outside of user configuration, like keybinds and scratchpads.

---

### File structure

- `assets`: images and svgs
- `base`: keybinds, autostart, scratchpad config
- `modules`: external libraries
- `signals`: for awm signals
- `theme`: theme variables and colorschemes
- `widget`: bar, launcher, notifications, titlebar config and others

- `helpers.lua`: helper functions
- `user.lua`: user configuration
- `rc.lua`: file that loads everything

---

### Keybinds

- `Super + Return` opens a terminal.
- `Super + /` shows the keybinds.

---

### TODO

- Control center widget
- Better keybinds popup
- Theme switcher
- Overall cleanup of code

---

### Gallery
<details>
<summary><b>Colorschemes</b></summary>

### Biscuit
![image](https://github.com/tsukki9696/tsukiyomi/assets/127806743/ca28a8a8-6ed8-464b-8758-94b76a2ecf4f)

### Oxocarbon
![image](https://github.com/tsukki9696/tsukiyomi/assets/127806743/c66cc039-02ac-4ffa-9e74-e4d6f669dfa8)

### Sakura
![image](https://github.com/tsukki9696/tsukiyomi/assets/127806743/8b5853bc-2610-405c-8376-33b31d2e7f9b)

### Camellia
![image](https://github.com/tsukki9696/tsukiyomi/assets/127806743/6087c1bb-7c65-4ae2-a541-df5b7b604db1)

### Adwaita
![image](https://github.com/tsukki9696/tsukiyomi/assets/127806743/87b7dee0-df40-4b29-afea-42ae37d0dc5e)

</details>

---

### Credits

- Stardust kyun's [Sakura dotfiles](https://github.com/Stardust-kyun/dotfiles) and support, since they gave me the courage needed to tackle this project and also some sweet reference for how to do things, also the nice colorscheme
- Gwynsav's gwdawful and [gwileful](https://github.com/Gwynsav/gwileful) rices, from which I borrowed some code, widgets and insight on how to execute ideas
- Chadcat's [Crystal](https://github.com/chadcat7/crystal) rice, for the battery and dock widgets
- Ner0z's [dotfiles](https://github.com/ner0z/dotfiles) for the music widget
- The [Unixporn discord server](https://discord.gg/unixporn) for a lot of insight and troubleshooting
- Nyoom for the [oxocarbon](https://github.com/nyoom-engineering/oxocarbon/tree/main) colorscheme
- Sinomor's [dotfiles](https://github.com/Sinomor/dotfiles) for some helper functions and the execution of inner and outer gaps
- My mom, she's very cool
