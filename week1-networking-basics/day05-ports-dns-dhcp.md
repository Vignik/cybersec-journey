# Day 5: Ports, DNS, and DHCP

## 📖 Topic
How specific services on a device are reached (ports), how domain names
become IP addresses (DNS), and how devices automatically get an IP (DHCP).

## 🧠 Key Concepts

- **Ports**: a number identifying a specific service/application on a
  device. An IP gets you to the device; a port gets you to the right
  service on it.
  - `80` — HTTP
  - `443` — HTTPS
  - `22` — SSH
  - `53` — DNS
  - `21` — FTP
  - *Example: `192.168.1.10:443` means "go to that device, talk to whatever
    is listening on port 443" (usually a web server).*

- **DNS (Domain Name System)**: translates human-readable domain names
  (`google.com`) into IP addresses (`142.250.190.14`) computers use.
  Think of it as the internet's phonebook.

- **DHCP (Dynamic Host Configuration Protocol)**: automatically assigns IP
  addresses to devices joining a network, so you don't have to configure
  one manually. Your router's DHCP server hands out a private IP when your
  phone joins the Wi-Fi.

## 💻 Practice Log
- [ ] Ran `nslookup` on 3 different websites, recorded the IPs returned

## 📝 My Notes (in my own words)
> List the 3 websites you looked up and their IPs. Explain DNS and DHCP in
> your own words.

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
