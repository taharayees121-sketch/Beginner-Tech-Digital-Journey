
# Networking Learning Notes

## Date
November 2, 2026

## What I learned

- **Network:** Connected computers and devices that communicate.
- **Router:** Connects different networks and directs data.
- **Switch:** Connects devices within a local network.
- **IP Address:** A numerical address used to identify a device on a network.
- **Subnet Mask:** Helps identify the network and host portions of an IP address.
- **Default Gateway:** The device that connects a local network to other networks.
- **DNS:** Domain Name System; translates domain names into IP addresses.
- **Ping:** Tests whether another device or server can be reached.
- **Traceroute:** Shows the network hops data travels through to reach a destination.
- **Hop:** One step through a network device along a route.

## Commands I practised

### 1. ipconfig
Displays network configuration details such as IP address, subnet mask, and default gateway.

Example:
```powershell
ipconfig
```

### 2. ping
Tests connectivity to another IP address.

Example:
```powershell
ping 8.8.8.8
```
Result: 4 packets sent, 4 received, 0% packet loss.

### 3. nslookup
Finds the IP address associated with a domain name.

Example:
```powershell
nslookup google.com
```
Result: Successfully returned Google's IPv4 and IPv6 addresses.

### 4. tracert
Shows the network route and hops to a destination.

Example:
```powershell
tracert google.com
```
Result: Reached Google in 6 hops. One intermediate hop timed out, but the destination was reached.

## Exercises completed

- Checked my laptop's network configuration.
- Tested internet connectivity using ping.
- Looked up Google's IP address using DNS.
- Traced the network route to Google.

## Problems I faced

- One intermediate hop in tracert showed Request timed out.
- Learned that some network devices do not respond to traceroute requests.

## Next steps

- Continue learning networking fundamentals.
- Understand IPv4, IPv6, and private versus public IP addresses.
- Practise more networking commands.

