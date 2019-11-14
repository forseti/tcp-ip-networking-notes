# TCP/IP Networking Notes

#### CIDR Notation

CIDR notation is a combination of an **IP Address** and its **Routing Prefix**: `<IP_ADDRESS>/<ROUTING_PREFIX>`

For example, If the CIDR notation is `192.168.100.20/24`:
- Its **IPv4 Address** is `192.168.100.20`
- Its **Routing Prefix** is `24`. It can be said that its **Network Mask** is `255.255.255.0`
- The first 24 bytes `192.168.100` is the **Network Address**
- The remaining bytes `20` is the **Host Address**

Another example, if the CIDR notation is `192.168.100.20/16`:
- Its **IPv4 Address** is `192.168.100.20`
- Its **Routing Prefix** is `16`. It can be said that its **Network Mask** is `255.255.0.0`
- The first 16 bytes `192.168` is the **Network Address**
- The remaining bytes `100.20` is the **Host Address**

The first address (0) in every network is reserved for **Network ID**
The last address (255) in every network is reserved for **Broadcast ID**

For example, if the CIDR Notation is `192.168.100.20/24`:
- Its **Network ID** is `192.168.100.0`
- Its **Broadcast ID** is `192.168.100.255`

| CIDR Notation | IPv4 Address | Routing Prefix | Network Mask | Network Address | Host Address | Network ID | Broadcast ID |
|---|---|---|---|---|---|---|---|
| `192.168.100.20/24` |`192.168.100.20`| `24` | `255.255.255.0` | `192.168.100` | `20` | `192.168.100.0` | `192.168.100.255` |


#### Private IP Address:
- `10.0.0.0/8`
- `172.16.0.0/12`
- `192.168.0.0/16`
