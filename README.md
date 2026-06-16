# bmpro-communications

Reverse engerineering the canbus protocol for bmpro battery management systems in caravans and rv
RJ12 - Std Color - 
1 - White -  GND
2 - Black -  GND
3 - Red -    CAN H
4 - Green -  CAN L
5 - Yellow - 12v
6 - Blue -   12v

script to connect and talk to a bmpro BP35 or J35 system

SSH as root
ip link set can0 down
ip link set can0 type can bitrate 125000
ip link set can0 up
