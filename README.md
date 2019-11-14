# TCP/IP Networking Notes

#### CIDR Notation

CIDR notation is a combination of an IP Address and its routing prefix:
`<IP_ADDRESS>/<ROUTING_PREFIX>`

For example, the CIDR notation of `192.168.100.20/24`:
- Its **IPv4 Address** is `192.168.100.20`
- Its **Routing Prefix** is `24`. It can be said that its **Network Mask** is `255.255.255.0`
- The first 24 bytes `192.168.100` is the **Network Address**
- The remaining bytes `20` is the **Host Address**

Another example, the CIDR notation of `192.168.100.20/16`:
- Its **IPv4 Address** is `192.168.100.20`
- Its **Routing Prefix** is `16`. It can be said that its **Network Mask** is `255.255.0.0`
- The first 16 bytes `192.168` is the **Network Address**
- The remaining bytes `100.20` is the **Host Address**


| CIDR Notation | IPv4 Address | Network Mask |
|---|---|---|
| `192.168.100.20/24` |`192.168.100.20`| `255.255.255.0` |



The first address in every network is **Network ID**
The last address in every network is **Broadcast ID**

#### Private IP Address:
- `10.0.0.0/8`
- `172.16.0.0/12`
- `192.168.0.0/16`
