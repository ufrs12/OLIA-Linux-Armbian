--- Network device support
[*]   Network core driver support
<M>     Bonding driver support
<M>     Dummy net driver support
<M>     WireGuard secure network tunnel
[ ]       Debugging checks and verbose messages
<M>     EQL (serial line load balancing) support
<M>     Intermediate Functional Block support
<M>     Ethernet team driver support  --->
<M>     MAC-VLAN support
<M>       MAC-VLAN based tap driver
<M>     IP-VLAN support
<M>       IP-VLAN based tap driver
<M>     Virtual eXtensible Local Area Network (VXLAN)
<M>     Generic Network Virtualization Encapsulation
<M>     Bare UDP Encapsulation
<M>     GPRS Tunneling Protocol datapath (GTP-U)
<M>     Automatic Multicast Tunneling (AMT)
<M>     IEEE 802.1AE MAC-level encryption (MACsec)
<M>     Network console logging support
[ ]       Dynamic reconfiguration of logging targets
[ ]       Set kernel extended message by default
<M>     Universal TUN/TAP device driver support
[ ]     Support for cross-endian vnet headers on little-endian kernels
<M>     Virtual ethernet pair device
<M>     Virtio network driver
<M>     Virtual netlink monitoring device
[ ]     BPF-programmable network device
< >     Virtual Routing and Forwarding (Lite)
<M>     MHI network driver
      Distributed Switch Architecture drivers  --->
[*]   Ethernet driver support  --->
-*-   PHY Device support and infrastructure  --->
< >   Micrel KS8995MA 5-ports 10/100 managed Ethernet switch
[ ]   Ethernet Power Sourcing Equipment Support  ----
<M>   CAN Device Drivers  --->                           
  -*-   MDIO bus device drivers  --->
       PCS device drivers  ----
<M>   PPP (point-to-point protocol) support
<M>     PPP BSD-Compress compression
<M>     PPP Deflate compression
[*]     PPP filtering
<M>     PPP MPPE compression (encryption)
[*]     PPP multilink support
<M>     PPP over Ethernet
          Number of PPPoE hash bits (4 bits (16 buckets))  --->
<M>     PPP over IPv4 (PPTP)
<M>     PPP over L2TP
<M>     PPP support for async serial ports
<M>     PPP support for sync tty ports
< >   SLIP (serial line) support
{M}   USB Network Adapters  --->
[*]   Wireless LAN  --->
  [ ]   Wan interfaces support  ----
<M>   IEEE 802.15.4 drivers  ----
      Wireless WAN  --->
<M>   Simulated networking device
{M}   Failover driver
[ ]   ISDN support  ----