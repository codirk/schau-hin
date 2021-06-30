# schau-hin
Raspberry PI based child protection

# Die Hardware
* Gehäuse für Raspberry Pi 4, Alu, schwarz
* Raspberry Pi 4 B, 4x 1,5 GHz, 8 GB RAM, WLAN, BT
* Raspberry Pi 4 - Kühlkörper 40 x 30 x 5 mm, schwarz
* MircoSD Card >8GB

# Setup
* https://www.raspberrypi.org/software/

# ssh aktivieren
```
systemctl start ssh
systemctl enable ssh
```
# dnsmaskd aktivieren
```
apt-get install net-tools
apt-get install dnsmasq
apt install dnsutils
systemctl start dnsmasq
``` 

add server
1.1.1.3
1.0.0.3

# squid proxy aktivieren
# calamaris (log analysis)
