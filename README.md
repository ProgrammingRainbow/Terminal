# Installing Alacritty and Fish
## Installing Alacritty
```
sudo pacman -S --needed alacritty
```
Add color themes to alacritty
```
mkdir -p ~/.config/alacritty/themes
git clone https://github.com/alacritty/alacritty-theme ~/.config/alacritty/themes
```
Add a default config for alacritty.
```
git clone https://github.com/ProgrammingRainbow/Alacritty-Fish
```
```
cp Alacritty-Fish/alacritty.toml ~/.config/alacritty/alacritty.toml
```
## Installing Fish
```
sudo pacman -S --needed fish
```
Add a default config file for fish.
```
mkdir -p ~/.config/fish/config.fish
cp Alacritty-Fish/config.fish ~/.config/fish/config.fish
```
Install eza, a replacement for ls.
```
sudo pacman -S --needed eza
```
Install starship shell prompt.
```
sudo pacman -S --needed starship
```
Build and install shell-color-scripts.
```
git clone https://gitlab.com/dwt1/shell-color-scripts.git
cd shell-color-scripts
makepkg -i
```




```
sudo pacman -S eza libgit2 http-parser
```
