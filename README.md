# volumecontrol

Small shell script to set volume programatically. The script is forked from
[hyprdots](https://github.com/prasanthrangan/hyprdots), and stripped from all
references to hyprland, to be used in any compositor/window manager.

## Installation

- Clone this repo

```bash
sudo make install
```

## Usage

```bash
volumecontrol -[device] <actions>
...valid device are...
    i   -- input device
    o   -- output device
    p   -- player application
...valid actions are...
    i   -- increase volume [+5]
    d   -- decrease volume [-5]
    m   -- mute [x]
```
