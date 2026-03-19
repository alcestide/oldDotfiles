# alk-Dotfiles
Ever-changing _ricing_,`*UNIX` and some `Windows` configurations. Work in progress.

I mostly use Windows and Arch-Linux with _tiling-wms_, especially Hyprland, [i3-wm](https://github.com/i3/i3) and currently [qtile](https://github.com/qtile/qtile) (even though I tend to wm-hop quite often 'cause I'm curious of the other alternatives). For what concerns _text editors_, I'm mostly a [Neovim](https://github.com/neovim/neovim) and [Doom Emacs](https://github.com/doomemacs/doomemacs) user, who sometimes also tinkers with JetBrains IDEs. 

Make sure to have all the proper **fonts** installed in your system (qtile require **ttf-icomoon-feather**, JetBrains Mono Nerd and Fira Code, but you should still be able to **change** them quite easily). 

The Qtile setup is based on a **two monitors** setup, but should also work just fine on single-monitor setups. If the config **doesn't properly load**, check `python -m ~/.config/qtile/config.py`, install the listed missing **modules** or simply fix the configuration file so it meets your needs.

**Colorschemes** are managed by `pywal` which generates them based on the wallpaper used. 

Start-up apps are handled by Qtile inside `.config/qtile/autostart.sh`, where I also specify my desired wallpaper using `wal`.

![2024-03-14_12-37](https://github.com/alcestide/oldDotfiles/assets/106203061/e7cffc48-7012-4014-8fec-1e4eae8bcab6)
![2023-05-23_18-36](https://github.com/alcestide/oldDotfiles/assets/106203061/410fe864-2921-49de-94d7-3cb85bec2cc4)
![2024-03-27_14-29](https://github.com/alcestide/oldDotfiles/assets/106203061/6e9ee860-6c28-48f4-9351-1d82c76833fb)

### **Table of Contents**
* [Configuration](#configuration)
  * [Included Files](#included-files) 
  * [Screenshots](#screenshots)
* [Qtile Keymaps](#qtile-keymaps)
* [Nvim Keymaps](#nvim-keymaps)

## Configuration <a name="configuration"></a>

- **Window Manager:** [Qtile](https://github.com/qtile/qtile) 

- **Shell:** [zsh](https://www.zsh.org/) + [oh-my-zsh](https://ohmyz.sh/)

- **Terminal:** [Alacritty](https://github.com/alacritty/alacritty)

- **GTK Theme:** [Material-Black-Blueberry](https://www.gnome-look.org/p/1316887)

- **Icon Theme** [Flat-Remix-Blue-Dark](https://www.gnome-look.org/p/1214931)

- **Mouse Cursor** [Bibata-Modern-Ice](https://www.gnome-look.org/p/1197198)

- **Notification Server** [Dunst](https://github.com/dunst-project/dunst)

- **Lockscreen:** [Betterlockscreen](https://github.com/betterlockscreen/betterlockscreen)

![2023-05-23_19-11](https://github.com/alcestide/Dotfiles/assets/106203061/40d19df5-920f-49e3-8857-408d7780c930)
![2023-07-11_13-17](https://github.com/alcestide/Dotfiles/assets/106203061/838b2042-585a-4fa1-adb7-73a5b542f072)

### Included Files <a name="included-files"></a>

- `.zshrc`
- `i3wm`
- `qtile`
- `picom`
- `dunst`
- `kitty`
- `alacritty`
- `doomemacs`
- `flameshot`
- `ranger`
- `nvim`
- `rofi`
- Docker-Compose Boilerplates
- X11 Miscellaneous Configurations
- Bash scripts to manage monitors, keyboard layouts and wallpapers

### Screenshots <a name="screenshots"> </a>

![2024-03-21_18-58](https://github.com/alcestide/Dotfiles/assets/106203061/0a39f29d-eb1d-4624-aa3a-d400b0fb42ac)
![2023-07-11_13-20](https://github.com/alcestide/Dotfiles/assets/106203061/28eca8a3-4f90-4823-9c57-5ec4daf7f703)
![2023-06-13_12-34](https://github.com/alcestide/Dotfiles/assets/106203061/2dd03ca6-4224-4171-a29a-813dc6fa000b)
![2023-05-25_00-50](https://github.com/alcestide/Dotfiles/assets/106203061/3b0cbbe4-dca3-49a0-8b67-772c43e80493)

## Qtile Keymaps <a name="qtile-keymaps"> </a>

- `Win + Enter` $\implies$ Open the terminal (Default: alacritty)
- `Win + X` $\implies$ Close focused window
- `Win + F` $\implies$ Toggle Fullscreen
- `Win + Shift + F` $\implies$ Toggle Floating
- `Win + Up/Down` $\implies$ Switch between windows
- `Win + Shift + [1,2,3,...,9]` $\implies$ Move window to specified workspace
- `Win + Tab` $\implies$ Next layout
- `Win + Shift + Tab` $\implies$ Previous layout
- `Win + Shift + Space` $\implies$ Switch between US and IT keyboard layout
- `F1` $\implies$ Switch focus to first monitor
- `F2` $\implies$ Switch focus to second monitor
- `Print` $\implies$ Flameshot Screenshot

## Nvim Keymaps <a name="nvim-keymaps"></a>

- `Ctrl + Arrows` $\implies$ Move between panes/windows
- `Ctrl + n` $\implies$ Toggle Oil
- `Ctrl + F5` $\implies$ Toggle Undotree
- `Space + ff` $\implies$ Open Telescope (Find Files)
- `Space + x` $\implies$ Close focused buffer
- `Space + [ or ]` $\implies$ Cycle through buffers
- `Space + S` $\implies$ Toggle Spectre
- `Ctrl + Spacebar` $\implies$ Accepts current LSP Completion
- `Alt + h` $\implies$ Toggle horizontal terminal
- `Alt + v` $\implies$ Toggle vertical terminal
- `Space + db` $\implies$ Toggle Nvim-dap Breakpoint
- `Space + dr` $\implies$ Nvim-dap Continue
- `Space + dt` $\implies$ Nvim-dap Terminate
