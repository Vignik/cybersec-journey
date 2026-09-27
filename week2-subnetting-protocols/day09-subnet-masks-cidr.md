# Day 9: Subnet Masks & CIDR

## 📖 Topic
A subnet mask tells you which part of an IP address is the "network" and
which part is the "host." CIDR notation is the shorthand for expressing this.

## 🧠 Key Concepts

- **Subnet mask**: a 32-bit number (like an IP) where 1s mark the network
  portion and 0s mark the host portion.
  *Example: `255.255.255.0` = network portion is first 3 octets, host
  portion is the last octet.*

- **CIDR notation**: `/n` where `n` = number of 1-bits (network bits).
  - `/24` = `255.255.255.0` (24 network bits, 8 host bits)
  - `/16` = `255.255.0.0` (16 network bits, 16 host bits)
  - `/8`  = `255.0.0.0` (8 network bits, 24 host bits)

- **More network bits = fewer hosts per subnet, but more subnets possible.**
  - `/24` → 256 addresses, 254 usable hosts
  - `/16` → 65,536 addresses
  - `/8`  → 16,777,216 addresses

- **Formula**: usable hosts = 2^(host bits) − 2
  (subtract 2 for network address and broadcast address, which aren't
  assignable to devices)
  *Example: `/24` → 8 host bits → 2^8 − 2 = 254 usable hosts*

## 💻 Practice Log
- [ ] Watched Professor Messer's subnetting video

## 📝 My Notes (in my own words)
> Explain what CIDR notation means and why more network bits = fewer hosts,
> in your own words.

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
