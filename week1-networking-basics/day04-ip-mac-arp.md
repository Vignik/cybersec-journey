# Day 4: IP Addresses, MAC Addresses, ARP

## 📖 Topic
How devices are identified on a network — logically (IP) and physically (MAC)
— and how ARP bridges the two.

## 🧠 Key Concepts

- **IP Address**: logical address assigned to a device, used for routing
  across networks. Format: `192.168.1.10` (IPv4).
  - **Private IP**: used inside a local network, not routable on the
    internet (ranges: `10.0.0.0/8`, `172.16.0.0/12`, `192.168.0.0/16`)
  - **Public IP**: the address your network shows to the internet
    (assigned by your ISP)
  - *Example: your laptop has a private IP like `192.168.1.15` at home, but
    your whole home network shares one public IP when reaching websites.*

- **MAC Address**: physical, hardware-burned address of a network interface
  card (NIC). Format: `00:1A:2B:3C:4D:5E`. Unique per device, doesn't change
  when you move networks (unlike IP).

- **ARP (Address Resolution Protocol)**: translates IP addresses to MAC
  addresses on a local network. When your device wants to send data to
  `192.168.1.1`, it broadcasts "who has this IP?" and the owning device
  replies with its MAC address.

## 💻 Practice Log
- [ ] Ran `ipconfig` (Windows) or `ip a` (Linux/Mac)
- [ ] Identified: my IP address, subnet mask, default gateway, MAC address

