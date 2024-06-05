
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


| Color              | Hex Code   | Visual                                       |
|--------------------|------------|----------------------------------------------|
| blue               | #0000FF    | ![#0000FF](https://via.placeholder.com/10/0000FF?text=+) |
| orange             | #FFA500    | ![#FFA500](https://via.placeholder.com/10/FFA500?text=+) |
| pink               | #FFC0CB    | ![#FFC0CB](https://via.placeholder.com/10/FFC0CB?text=+) |
| magenta            | #FF00FF    | ![#FF00FF](https://via.placeholder.com/10/FF00FF?text=+) |
| green              | #008000    | ![#008000](https://via.placeholder.com/10/008000?text=+) |
| red                | #FF0000    | ![#FF0000](https://via.placeholder.com/10/FF0000?text=+) |
| yellow             | #FFFF00    | ![#FFFF00](https://via.placeholder.com/10/FFFF00?text=+) |
| cyan               | #00FFFF    | ![#00FFFF](https://via.placeholder.com/10/00FFFF?text=+) |
| white              | #FFFFFF    | ![#FFFFFF](https://via.placeholder.com/10/FFFFFF?text=+) |
| gray               | #808080    | ![#808080](https://via.placeholder.com/10/808080?text=+) |
| mauve              | #C6A0F6    | ![#C6A0F6](https://via.placeholder.com/10/C6A0F6?text=+) |
| rosewater          | #F4DBD6    | ![#F4DBD6](https://via.placeholder.com/10/F4DBD6?text=+) |
| flamingo           | #F0C6C6    | ![#F0C6C6](https://via.placeholder.com/10/F0C6C6?text=+) |
| lavender           | #B7BDF8    | ![#B7BDF8](https://via.placeholder.com/10/B7BDF8?text=+) |
| navy               | #0a192f    | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) |
| light gray         | #f8f8f8    | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) |
| teal               | #00b48a    | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) |
| light teal         | #00d1a0    | ![#00d1a0](https://via.placeholder.com/10/00d1a0?text=+) |
| fresh green        | #A6DA95    | ![#A6DA95](https://via.placeholder.com/10/A6DA95?text=+) |
| catppuccin mocha   | #4B4152    | ![#4B4152](https://via.placeholder.com/10/4B4152?text=+) |
| catppuccin frappe  | #C2A494    | ![#C2A494](https://via.placeholder.com/10/C2A494?text=+) |
| catppuccin macchiato | #9D795C  | ![#9D795C](https://via.placeholder.com/10/9D795C?text=+) |
| catppuccin latte   | #D6D2C4    | ![#D6D2C4](https://via.placeholder.com/10/D6D2C4?text=+) |
| pastel pink        | #EDB3C7    | ![#EDB3C7](https://via.placeholder.com/10/EDB3C7?text=+) |
| pastel yellow      | #F3F3BC    | ![#F3F3BC](https://via.placeholder.com/10/F3F3BC?text=+) |
| pale blue          | #9CC5E3    | ![#9CC5E3](https://via.placeholder.com/10/9CC5E3?text=+) |
| pale green         | #BDE9BE    | ![#BDE9BE](https://via.placeholder.com/10/BDE9BE?text=+) |
| pale purple        | #B19CD9    | ![#B19CD9](https://via.placeholder.com/10/B19CD9?text=+) |
| gruvbox black      | #282828    | ![#282828](https://via.placeholder.com/10/282828?text=+) |
| gruvbox red        | #cc241d    | ![#cc241d](https://via.placeholder.com/10/cc241d?text=+) |
| gruvbox green      | #98971a    | ![#98971a](https://via.placeholder.com/10/98971a?text=+) |
| gruvbox yellow     | #d79921    | ![#d79921](https://via.placeholder.com/10/d79921?text=+) |
| gruvbox blue       | #458588    | ![#458588](https://via.placeholder.com/10/458588?text=+) |
| gruvbox magenta    | #b16286    | ![#b16286](https://via.placeholder.com/10/b16286?text=+) |
| gruvbox cyan       | #689d6a    | ![#689d6a](https://via.placeholder.com/10/689d6a?text=+) |
| gruvbox white      | #a89984    | ![#a89984](https://via.placeholder.com/10/a89984?text=+) |




## Documentation

to edit the config, go to
~/.config/lsm/config

**DONT USE THE HEX CODES USE THE NAMES OF THE COLORS ABOVE**
