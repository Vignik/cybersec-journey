# Day 6: Wireshark — Capturing Your Own Traffic

## 📖 Topic
Wireshark is a packet analyzer — it lets you see the actual data traveling
across your network interface in real time.

## 🧠 Key Concepts

- **Packet capture**: Wireshark listens on a network interface and logs
  every packet passing through, showing source/destination, protocol, and
  payload.

- **Reading a DNS request in Wireshark**: filter with `dns` — you'll see a
  query packet (asking "what's the IP for x.com?") followed by a response
  packet containing the answer.

- **Reading a TCP handshake in Wireshark**: filter with `tcp.flags.syn==1`
  or just look for the `SYN`, `SYN, ACK`, `ACK` sequence in the Info column
  — this is Day 3's handshake, now visible.

## 💻 Practice Log
- [ ] Installed Wireshark
- [ ] Captured live traffic on my main interface
- [ ] Found and filtered a DNS request (`dns` filter)
- [ ] Found and filtered a TCP handshake (`tcp.flags.syn==1`)
- [ ] Took a screenshot of both, saved to `/images`

## 📝 My Notes (in my own words)
> Describe what you saw: which site triggered the DNS request, which
> connection showed the handshake. Link your screenshot:
> `![wireshark capture](../images/day06-wireshark.png)`

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
