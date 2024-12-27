# 🖧 A Network Topology designed using Cisco Packet Tracer

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)



## Designed Network
![network_screenshot](https://github.com/user-attachments/assets/bf7b73c1-8adc-44b7-beb6-6f87d1241bdf)


## Explanations
The topolgy of this project has been devided into 4 sections and a backbone. Different protocols has been confgured in routers like [OSPF](https://www.ietf.org/rfc/rfc2328.txt), [RIP](https://datatracker.ietf.org/doc/html/rfc2453), [EIGRP](https://datatracker.ietf.org/doc/html/rfc7868) and [HSRP](https://datatracker.ietf.org/doc/html/rfc2281).in some routers, protocols have been redistributed.Also layer 2 switches and layer 3 switches were configured to have vlans and inter vlan routing. Devices behind wireless routers in Japan section use NAT protocl and so thier ip addresses are private.Some security aspects have been considered, for example defining blackhole vlans.Also an CAL has been defined to deny access printer outside of IUT LAN.There also some servers for example email server, web server , DHCP server and DNS server, so you can make an account in email server and then try to send an email with devices.
You can simply all of the configurations, using ```show ru ``` command in each device.


## Constraints


## How to Run
Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) and then simply open the [netlab_project.pkt](netlab_project.pkt). The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.You should wait some seconds until 







