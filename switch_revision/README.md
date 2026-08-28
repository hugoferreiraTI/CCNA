================================================

                  NY_1 ROUTER

               RESTRICTED ACCESS

hostname: NY_1

GE 0/0/0 ip address is 192.168.1.1 /24 the others ports is desactivade.

llpd activade.

The secret for priviligie mod is cisco.

================================================

================================================

                 S_CORE

This switch is root bridge with priority in 0

The secret for priviligie mod is cisco.

Interface GigabitEthernet0/2, changed state to administratively down

interface FastEthernet 0/1 - 3 and GigabitEthernet 0/1 chang mod TRUNK and dto1q 

we created four vlan, vlan 999 for connection, vlan 10 for rh, vlan 20 for TI and vlan 30 for call-center.

vlan10: 192.168.10.1 /24 - gateway

vlan20: 192.168.20.1 /24 - gateway

vlan30: 192.168.30.1 /24 - gateway

llpd activade.


================================================

                S_TI

This switch to beloing vlan10 in segment TI

The interface F 0/1 is trunk mode

F 0/5 - 10 beloing the vlan 20 

Server tftp ip: 192.168.20.5

================================================

                S_CALL

This switch to beloing vlan30 and 50 for voice in segmento call center

the interface F 0/1 is trunk mode

F 0/5 - 15 beloing the vlan 30 and 50

the interface f 0/5 - 15 this in access mode


================================================

                S_rh

This switch to beloing vlan10

the interface F 0/1 is trunk mode

F 0/5 - 10 beloing the vlan 10 and function in portfast mode with bpdufilter

the interface f 0/5 - 10 is acces mode



