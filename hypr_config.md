# HYPRLAND CONFIGURATION

- Wayland Compositor: hyprland
- Shell: fish
- Prompt: starship
- Browser: firefox
- Terminal Emulator: 
    + alacritty
    + foot
- Launcher: rofi-lbonn
- Fonts:
    + Terminal/Programming: JetBrains Mono Nerd Font
    + System: RobotoMono Nerd Font
- Bar: 
    + waybar-hyprland-git
    *test if waybar main works with hyprland now*
- GUI File Manager:
    + Thunar (with tumbler plugin)
- TTY File Manager: Ranger

- Themes: 
    + Catpuccin mocha
    + Gruvbox Material
- Icons: papirus Icons
- Gtk appearance: nwg-look-bin
- Wallpaper tool: hyprpaper
- Image viewer: swayimg
- PDF Viewer: zathura + *plugin: mupdf*
- Cursor: captain cursor
- Notifications: dunst

- 

# TASKS
- GIT
  - Better dotfiles configuration (push/pull)

- Improve prompt (can be done without custom rice)

- Install greetd with desired theme

- Theme, improve design and set up swaylock

- Set up dunst properly (all: interaction with system, hyprland...)

- Better keyboard shortcuts (add good workspaces swap)

- Auto mounting (easy, with terminal[remember how] and with thunar)

- Adjust customization:
  + new language keyboard
  + waybar
    + styles
    + modules
    + two times same module different config between them but
    + click events
    + better config
    + keyboard layout change
    + hover labels
    + widgets
    + themes
  + neovim (lazy.vim)
    > I have decent config now (best colorscheme, no notifications)
    + test autocompletions, read documentation about
      lazy.vim
      lazyvim distro
    + read and search about plugins, how they work...
      + debug
  + see for new/better rofi style


# LOAD GRUVBOX MATERIAL IN LAZYVIM

set background=dark
colorscheme = 'gruvbox-material'

init = function()
  vim.g.copilot_no_tab_remap = false
end

# CHANGE WALLPAPERS TO A CERTAIN colorscheme
imagegonord
