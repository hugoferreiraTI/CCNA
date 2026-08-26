============================================================

                  DOCUMENTATION FOR NETWORK

============================================================

============================================================

                           ROUTER

Ip: 192.168.1.1 /24

ip domain-name: net.com

lldp: active

RSA created with 1024 bits and ip domain-name

username cisco password cisco

SSH: active in vty 0 2 more disebla.

============================================================

============================================================

                         S_CORE 

Type: Switch multi layer (L3)

Ip address: 192.168.1.2 /24

ip domain-name: net.com

rsa active with 1024 bits and ip domain-name

username cisco password cisco

transport with ssh in vty 0 2 more disable

password secret: ecisco

Port GE 1/0/1 - 19 is in administravitily down

Port GE 1/0/20 - 24 is in trunk mode

Router conect in port 1/0/20

Server_tftp conect in port 1/0/1

Vlans:

Vlan10 have the ip 192.168.10.1 /24

Vlan20 have the ip 192.168.20.1 /24

Vlan30 have the ip 192.168.30.1 /24 only voice vlan

this switch is the root bridge.

priority is 0

============================================================

                         S_RH

F 0/1 - 2 in vlan10 and f0/1 in vlan30 for voice 

f0/1 until f0/22 is in mode acess

f0/23 - 24 is in mode trunk and portchannel

g0/1 - 2 is in mode trunk

hostname: S_rh

============================================================

                         S_financy

F 0/1 - 2 in vlan20 this port is working with BPDUGUARD and portFast

f0/1 until f0/22 is in mode acess

g0/1 - 2 is in mode trunk

f0/23 - 24 is in mode trunk and portchannel

hostname: S_financiy

ip domain-name is net.com





