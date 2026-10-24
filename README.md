<p align="center">
<img src="https://raw.github.com/eldritch-theme/eldritch/master/assets/logo/logo.png" width=150>
</p>
<p>
Eldritch is a community-driven dark theme inspired by Lovecraftian horror. With tones from the dark abyss and an emphasis on green and blue, it caters to those who appreciate the darker side of life.
</p>

Main Theme repo can be found [here](https://github.com/eldritch-theme/eldritch)

### Showcase:
<img width="3429" height="1433" alt="preview" src="https://github.com/user-attachments/assets/8ffe573c-5548-43d2-b61c-a34e8527cd72" />
<img width="909" height="784" alt="image" src="https://github.com/user-attachments/assets/2801c667-b773-4aed-b0ad-16a29e196d05" />
<img width="882" height="606" alt="image" src="https://github.com/user-attachments/assets/d56ae83f-bbb9-42e6-b656-225777e1cff6" />

### Installation (Omarchy 4 / Quattro):
Omarchy ignores `*.lua`, terminal configs and `vscode.json` from themes cloned
straight into `~/.config/omarchy/themes` (it detects the `.git` directory), which
would drop the animations, Neovim and VS Code themes. Clone the repo elsewhere and
symlink it instead:

```
git clone https://github.com/Pahmaton/omarchy-eldritch-custom.git ~/Projects/omarchy-eldritch-custom
ln -s ~/Projects/omarchy-eldritch-custom ~/.config/omarchy/themes/omarchy-eldritch-custom
omarchy theme set omarchy-eldritch-custom
```

#### Remove Opacity
Add this to the end of `~/.config/hypr/hyprland.lua`:
```lua
-- Force full opacity (overrides default Omarchy opacity rules)
o.window({ tag = "default-opacity" }, { opacity = "1 1" })
```
