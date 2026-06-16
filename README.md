# bmpro-communications

Reverse engerineering the canbus protocol for bmpro battery management systems in caravans and rv

Blue -   12v
Yellow - 12v
Green -  CAN L
Red -    CAN H
Black -  GND
White -  GND

script to connect and talk to a bmpro BP35 or J35 system

SSH as root
ip link set can0 down
ip link set can0 type can bitrate 125000
ip link set can0 up
