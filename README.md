
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
Find the colors you want, for the folders ill use 
Lavender, for the files ill use Flamingo.

this is what it would look like:
```bash

# Configuration for lsm script

# Define colors for folders and files using the function names in the script
Color_Folder='lavender'
Color_File='flamingo'

# Option to show hidden files (.dot files)
Show_Dots='true'

```
make sure to use lowercase so Flamingo would be flamingo.
Get the colors from below.

## Colors:
| Color      | Hex Code   | Visual                                       |
|------------|------------|----------------------------------------------|
| blue       | #0000FF    | ![#0000FF](https://via.placeholder.com/10/0000FF?text=+) |
| orange     | #FFA500    | ![#FFA500](https://via.placeholder.com/10/FFA500?text=+) |
| pink       | #FFC0CB    | ![#FFC0CB](https://via.placeholder.com/10/FFC0CB?text=+) |
| magenta    | #FF00FF    | ![#FF00FF](https://via.placeholder.com/10/FF00FF?text=+) |
| green      | #008000    | ![#008000](https://via.placeholder.com/10/008000?text=+) |
| red        | #FF0000    | ![#FF0000](https://via.placeholder.com/10/FF0000?text=+) |
| yellow     | #FFFF00    | ![#FFFF00](https://via.placeholder.com/10/FFFF00?text=+) |
| cyan       | #00FFFF    | ![#00FFFF](https://via.placeholder.com/10/00FFFF?text=+) |
| white      | #FFFFFF    | ![#FFFFFF](https://via.placeholder.com/10/FFFFFF?text=+) |
| gray       | #808080    | ![#808080](https://via.placeholder.com/10/808080?text=+) |
| mauve      | #C6A0F6    | ![#C6A0F6](https://via.placeholder.com/10/C6A0F6?text=+) |
| rosewater  | #F4DBD6    | ![#F4DBD6](https://via.placeholder.com/10/F4DBD6?text=+) |
| flamingo   | #F0C6C6    | ![#F0C6C6](https://via.placeholder.com/10/F0C6C6?text=+) |
| lavender   | #B7BDF8    | ![#B7BDF8](https://via.placeholder.com/10/B7BDF8?text=+) |
| navy       | #0a192f    | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) |
| light Gray | #f8f8f8    | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) |
| teal       | #00b48a    | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) |
| light_teal | #00d1a0    | ![#00d1a0](https://via.placeholder.com/10/00d1a0?text=+) |

## Documentation

to edit the config, go to
~/.config/lsm/config

**DONT USE THE HEX CODES USE THE NAMES OF THE COLORS ABOVE**
