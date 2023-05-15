C:\Users\ishik>nslookup www.facebook.com
Server:  UnKnown
Address:  192.168.1.1

Non-authoritative answer:
DNS request timed out.
    timeout was 2 seconds.
Name:    star-mini.c10r.facebook.com
Address:  157.240.239.35
Aliases:  www.facebook.com


C:\Users\ishik>nslookup www.google.com
Server:  UnKnown
Address:  192.168.1.1

Non-authoritative answer:
Name:    www.google.com
Addresses:  2404:6800:4002:81f::2004
          142.250.193.36


C:\Users\ishik>nslookup www.github.com
Server:  UnKnown
Address:  192.168.1.1

Non-authoritative answer:
Name:    github.com
Address:  20.207.73.82
Aliases:  www.github.com


C:\Users\ishik>ipconfig/all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : DESKTOP-TLOI49H
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek PCIe GbE Family Controller
   Physical Address. . . . . . . . . : D4-5D-64-69-89-3C
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter
   Physical Address. . . . . . . . . : DA-C0-A6-B1-D9-91
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #2
   Physical Address. . . . . . . . . : EA-C0-A6-B1-D9-91
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Qualcomm Atheros QCA9377 Wireless Network Adapter
   Physical Address. . . . . . . . . : D8-C0-A6-B1-D9-91
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::9802:9ab8:ba5f:f08e%15(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.1.104(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 15 May 2023 19:34:52
   Lease Expires . . . . . . . . . . : 15 May 2023 21:34:52
   Default Gateway . . . . . . . . . : 192.168.1.1
   DHCP Server . . . . . . . . . . . : 192.168.1.1
   DHCPv6 IAID . . . . . . . . . . . : 165200038
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-27-3D-17-80-D4-5D-64-69-89-3C
   DNS Servers . . . . . . . . . . . : 192.168.1.1
   NetBIOS over Tcpip. . . . . . . . : Enabled

C:\Users\ishik>ping 157.240.239.35

Pinging 157.240.239.35 with 32 bytes of data:
Reply from 157.240.239.35: bytes=32 time=39ms TTL=56
Reply from 157.240.239.35: bytes=32 time=28ms TTL=56
Reply from 157.240.239.35: bytes=32 time=44ms TTL=56
Reply from 157.240.239.35: bytes=32 time=60ms TTL=56

Ping statistics for 157.240.239.35:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 28ms, Maximum = 60ms, Average = 42ms

C:\Users\ishik>ping 192.168.1.1

Pinging 192.168.1.1 with 32 bytes of data:
Reply from 192.168.1.1: bytes=32 time=8ms TTL=64
Reply from 192.168.1.1: bytes=32 time=10ms TTL=64
Reply from 192.168.1.1: bytes=32 time=11ms TTL=64
Reply from 192.168.1.1: bytes=32 time=19ms TTL=64

Ping statistics for 192.168.1.1:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 8ms, Maximum = 19ms, Average = 12ms

C:\Users\ishik>
