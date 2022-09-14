## battery-duo
Simple module showing battery percentage on systems with one or two batteries(such as Thinkpad with Power Bridge). Features 4 options to display current battery capacity.

Display with Unicode Emojis

![](pics/battery-duo.png)![](pics/battery-duo-charge.png)

Display with Font Awesome/Nerd-Fonts

![](pics/battery-duo-a.png) ![](pics/battery-duo-a-charge.png)

Simple Display

![](pics/battery-duo-s.png)

Display only percentage

![](pics/battery-duo-0.png)


## Features
* caluculates current capacity through /sys/class/power_supply
* configuration of display through arguments

## Dependency
* if you'd like to use battery-duo -a you do need font awesome or nerd fonts

## Setup
Download at least the battery-duo script file and place in a Direcotry you desire. Make it executable with *chmod +x battery-poly*. Add the following to your i3blocks config and modify to your liking:
```
[battery-duo]
command=/path/to/file/battery-duo
interval=5
```
