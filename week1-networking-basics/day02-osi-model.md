# Day 2: The OSI Model (7 Layers)

## 📖 Topic
The OSI model is a 7-layer conceptual framework describing how data travels
from one device to another across a network — from the physical cable up to
the application you're using.

## 🧠 Key Concepts

| Layer | Name         | What it does                          | Example                          |
|-------|--------------|----------------------------------------|-----------------------------------|
| 7     | Application  | The interface you interact with        | Chrome, email client              |
| 6     | Presentation | Formats/encrypts data                  | SSL/TLS encryption, file formats  |
| 5     | Session      | Manages connections between apps       | Login session staying open        |
| 4     | Transport    | Reliable delivery, breaks into segments| TCP, UDP                          |
| 3     | Network      | Routing, logical addressing            | IP addresses, routers             |
| 2     | Data Link    | Physical addressing on local network   | MAC addresses, switches           |
| 1     | Physical     | The actual hardware/signal             | Cables, Wi-Fi radio waves, NICs   |

- **Encapsulation**: as data moves down the layers (from app to physical),
  each layer wraps the data in its own header — like nesting envelopes
  inside envelopes. The receiving device unwraps them in reverse order.

## 🧠 Memory Trick
Top to bottom (7→1): **A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**izza
(Application, Presentation, Session, Transport, Network, Data Link, Physical)

## 💻 Practice Log
- [ ] Watched NetworkChuck's OSI model video
- [ ] Wrote my own memory trick

## 📝 My Notes (in my own words)
> Explain what OSI is for and why splitting networking into layers is useful
> (hint: think about troubleshooting — if something's broken, which layer
> would you check?).

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
