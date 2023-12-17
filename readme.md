# Needed settings for custom checks.

## RPI
```
usermod -a -G video zabbix
```

## Screen-color
```
apt install maim imagemagick
/home/monitor/.xinitrc: /usr/bin/xhost +SI:localuser:zabbix
```