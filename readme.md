# Needed settings for custom checks.

## Docker
```
usermod -a -G docker zabbix
```

## RPI
```
usermod -a -G video zabbix
```

## Screen-color
```
apt install maim imagemagick
/home/monitor/.xinitrc: /usr/bin/xhost +SI:localuser:zabbix
```
