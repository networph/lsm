
# Lsm.

lsm is a modded ls with nice colors and an easy config file.
You can even add your own colors if you want. I will add tons of colors each day, mostly. And I will also add more stuff and nice features.
## Installation

The Installation. 

Installing Git


 1. Arch Linux
```bash
sudo pacman -S git
```
 2. Fedora
```bash
sudo dnf install git
```

 3. Ubuntu/Debian
```
sudo apt install git
```
then,
```bash
cd
git clone https://github.com/networph/lsm
cd lsm
cd lsm
sudo mv lsm /usr/local/bin/lsm
cd /usr/local/bin
sudo chmod +x lsm
```



IF THAT DOESNT WORK REMOVE THE FIRST cd 

Now, restart and you should be good!
## How to make your config?
```bash
cd ~/.config
sudo mkdir lsm
cd lsm
sudo nano config
```
## What to put in your config.
Find below the colors you want, for the folders ill use 
Lavender, for the files ill use Flamingo.

this is what it would look like:
```bash
Color_Folder='lavender'
Color_File='flamingo'
```
make sure to use lowercase so Flamingo would be flamingo.
Get the colors from below.

## Colors:
| Color      | Hex Code   | Visual                                       |
|------------|------------|----------------------------------------------|
| Blue       | #0000FF    | ![#0000FF](https://via.placeholder.com/10/0000FF?text=+) |
| Orange     | #FFA500    | ![#FFA500](https://via.placeholder.com/10/FFA500?text=+) |
| Pink       | #FFC0CB    | ![#FFC0CB](https://via.placeholder.com/10/FFC0CB?text=+) |
| Magenta    | #FF00FF    | ![#FF00FF](https://via.placeholder.com/10/FF00FF?text=+) |
| Green      | #008000    | ![#008000](https://via.placeholder.com/10/008000?text=+) |
| Red        | #FF0000    | ![#FF0000](https://via.placeholder.com/10/FF0000?text=+) |
| Yellow     | #FFFF00    | ![#FFFF00](https://via.placeholder.com/10/FFFF00?text=+) |
| Cyan       | #00FFFF    | ![#00FFFF](https://via.placeholder.com/10/00FFFF?text=+) |
| White      | #FFFFFF    | ![#FFFFFF](https://via.placeholder.com/10/FFFFFF?text=+) |
| Gray       | #808080    | ![#808080](https://via.placeholder.com/10/808080?text=+) |
| Mauve      | #C6A0F6    | ![#C6A0F6](https://via.placeholder.com/10/C6A0F6?text=+) |
| Rosewater  | #F4DBD6    | ![#F4DBD6](https://via.placeholder.com/10/F4DBD6?text=+) |
| Flamingo   | #F0C6C6    | ![#F0C6C6](https://via.placeholder.com/10/F0C6C6?text=+) |
| Lavender   | #B7BDF8    | ![#B7BDF8](https://via.placeholder.com/10/B7BDF8?text=+) |
| Navy       | #0a192f    | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) |
| Light Gray | #f8f8f8    | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) |
| Teal       | #00b48a    | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) |
| Light Teal | #00d1a0    | ![#00d1a0](https://via.placeholder.com/10/00d1a0?text=+) |


## Documentation

to edit the config, go to
~/.config/lsm/config

**DONT USE THE HEX CODES USE THE NAMES OF THE COLORS ABOVE**
