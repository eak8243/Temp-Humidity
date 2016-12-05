# Temp-Humidity

>sudo apt-get install minicom 

>sudo minicom -b 9600 -o -D /dev/ttyAMA0

>sudo sysctl -p

>sudo systemctl disable serial-getty@ttyAMA0.service

###FTP

>sudo apt-get install vsftpd

>edit: sudo nano /etc/vsftpd.conf

>write_enable=yes

###Autorun python

>create file run_python.sh

>>\#! /bin/bash

>>sudo python /home/pi/Desktop/main.py

>chmod +x main.py
