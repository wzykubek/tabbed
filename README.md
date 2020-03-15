# tabbed

## Description
Simple generic tabbed fronted to xembed aware applications, originally designed for surf but also usable with many other applications, i.e. st, uzbl, urxvt and xterm.

## Installation
```
sudo make clean install
```

## Usage
#### st
```
tabbed -r 2 st -w ''
```

### Bindings
MOD = Control

Binding | Action
:--- | :---
MOD + Shift + Enter | open new tab
MOD + Shift + j | go to next tab
MOD + Shift + k | go to previous tab
MOD + Shift + h | move tab to left side
MOD + Shift + l | move tab to right side
MOD + Tab | switch between two tabs
MOD + [Num] (e.g. 1) | switch to specified tab
MOD + q | kill current tab
