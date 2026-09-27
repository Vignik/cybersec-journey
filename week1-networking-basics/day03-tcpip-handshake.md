# Day 3: TCP/IP Model, TCP vs UDP, 3-Way Handshake

## 📖 Topic
The TCP/IP model is the practical 4-layer model actually used on the
internet (a simplified version of OSI). TCP and UDP are the two main
transport protocols, with very different guarantees.

## 🧠 Key Concepts

- **TCP/IP model (4 layers)**: Application, Transport, Internet, Network Access
  — maps roughly onto OSI's 7 layers but is what's actually implemented.

- **TCP (Transmission Control Protocol)**:
  - Connection-oriented, reliable, ordered
  - Confirms every packet arrived (retransmits if lost)
  - Slower but guaranteed delivery
  - *Example: loading a webpage, sending an email — you need every byte to
    arrive correctly.*

- **UDP (User Datagram Protocol)**:
  - Connectionless, no delivery guarantee, no ordering
  - Faster, lower overhead
  - *Example: video calls, live streaming, online gaming — a dropped frame
    is fine, but a laggy delayed frame is worse.*

- **The TCP 3-Way Handshake** (how a TCP connection starts):
  1. Client sends **SYN** ("can we talk?")
  2. Server replies **SYN-ACK** ("yes, and can you hear me?")
  3. Client replies **ACK** ("yes, let's go")
  → Connection is now established, data transfer begins.

## 💻 Practice Log
- [ ] Completed THM Pre Security networking room(s)

## 📝 My Notes (in my own words)
> Explain TCP vs UDP with your own example, and walk through the 3-way
> handshake in your own words like you're explaining it to a friend.

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
