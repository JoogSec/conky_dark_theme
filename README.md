# How does it looks like
![alt text](https://github.com/thaJoog/conky_theme/blob/master/conky_rc.png "THEME")


# Install
Debian:
  `sudo apt install conky conky-all`

Arch-Linux:
  https://wiki.archlinux.org/index.php/conky

# Install conky-draw
  https://github.com/fisadev/conky-draw
  
# Setup Conky
Clone or download the files from here and copy everything into the ~/.conkyrc so after all the structure should look like this

- conky_draw_config.lua
- conky_draw.lua
- conkyrc
- startConky.sh

# Start
Manually you can start with `conky -c conkyrc` or you can use the start script, attention if you use the script there is a delay around 10 seconds which you need if you want to use it for the autostart routine.
