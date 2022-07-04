# qtile
## Installation
git clone git@github.com:holovin777/qtile.git

## Configuration
```bash
sudo pacman -S acpilight
ls /sys/class/backlight/
vim ~/.config/qtile/config.py
```
Change your backlight name
```python

                widget.Backlight(
                    backlight_name='amdgpu_bl0',
                    change_command="xbacklight -set {0}",
                    foreground="#CD8A8A"
                ),
```
