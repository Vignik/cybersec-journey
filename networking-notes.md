# 🌐 Networking Notes — Index

This file is the master index for all networking concepts. Full
explanations, examples, and my own written notes live in each day's file
under `week1-networking-basics/` and `week2-subnetting-protocols/`.

## Week 1 — Networking Basics
- [Day 1: What is a Network?](week1-networking-basics/day01-setup-what-is-a-network.md)
- [Day 2: OSI Model](week1-networking-basics/day02-osi-model.md)
- [Day 3: TCP/IP, TCP vs UDP, 3-Way Handshake](week1-networking-basics/day03-tcpip-handshake.md)
- [Day 4: IP, MAC, ARP](week1-networking-basics/day04-ip-mac-arp.md)
- [Day 5: Ports, DNS, DHCP](week1-networking-basics/day05-ports-dns-dhcp.md)
- [Day 6: Wireshark](week1-networking-basics/day06-wireshark.md)
- [Day 7: Week 1 Revision](week1-networking-basics/day07-revision-quiz.md)

## Week 2 — Subnetting + Protocols
- [Day 8: Binary Basics](week2-subnetting-protocols/day08-binary-basics.md)
- [Day 9: Subnet Masks & CIDR](week2-subnetting-protocols/day09-subnet-masks-cidr.md)
- [Day 10: Subnetting by Hand](week2-subnetting-protocols/day10-subnetting-by-hand.md)
- [Day 11: More Subnetting Practice](week2-subnetting-protocols/day11-subnetting-practice.md)
- [Day 12: HTTP/HTTPS](week2-subnetting-protocols/day12-http-https.md)
- [Day 13: Firewalls, NAT, VPN](week2-subnetting-protocols/day13-firewalls-nat-vpn.md)
- [Day 14: Checkpoint 1](week2-subnetting-protocols/day14-checkpoint1.md)

## Quick Reference — Subnetting Formula
- Usable hosts = 2^(host bits) − 2
- Block size = 256 − (interesting octet of the subnet mask)
- Network address = round IP down to nearest block boundary
- Broadcast address = next block boundary − 1
