#!/bin/bash
echo -e "\e[91m
-------------------------
.                       .
.       Easy install    .
.               by      .
.       Zhermina        .
.                       .
-------------------------
"
sleep 1s
git clone https://github.com/deltaxflux/fluxion
echo "Fluxion downloaded."
cd fluxion/
apt-get install isc-dhcp-server -y
apt-get install hostapd -y
apt-get install lighttpd -y
apt-get install php-cgi -y
clear
echo -e " 
-----------------
.               .
.               .
.    Ready :)   .
.               .
.               .
-----------------
"
sleep 1s
./fluxion
