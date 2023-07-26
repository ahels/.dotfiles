# HYPRLAND CONFIGURATION

- Wayland Compositor: hyprland
- Shell: fish
- Prompt: starship
- Browser: firefox
- Terminal Emulator: alacritty
- Launcher: rofi-lbonn
- Fonts:
    + Terminal/Programming: JetBrains Mono Nerd Font
    + System: RobotoMono Nerd Font
- Bar: waybar-hyprland-git
- GUI File Manager:
    + Thunar or Nemo
- TTY File Manager: Ranger

- Themes: 
    + Catpuccin mocha
    + Gruvbox Material
- Icons: papirus Icons
- Gtk appearance: nwg-look-bin
- Wallpaper tool: hyprpaper
- Image viewer: swayimg
- PDF Viewer: zathura + *plugin: mupdf*




- Cursor
- 

# TASKS
- GIT

- Adjust customization:
  + new language keyboard
  + waybar
    + styles
    + modules
  + neovim (lazy.vim)



# LOAD GRUVBOX MATERIAL IN LAZYVIM

set background=dark
colorscheme = 'gruvbox-material'

init = function()
  vim.g.copilot_no_tab_remap = false
end


# CHANGE WALLPAPERS TO A CERTAIN colorscheme
imagegonord
