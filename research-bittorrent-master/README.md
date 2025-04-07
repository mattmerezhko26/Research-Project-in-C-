# BitTorrent Protocol Implementation – C# Project

## 📌 Purpose

This project is a simplified implementation of the BitTorrent protocol written in C#. BitTorrent is a peer-to-peer (P2P) file-sharing protocol that allows users to distribute files across a decentralized network. Rather than downloading from a single source, peers exchange file pieces with each other, increasing download efficiency and resilience.

The primary goal of this project was to understand the low-level mechanics of BitTorrent — including how files are split into chunks, how peers discover each other, and how file integrity is ensured using cryptographic hashes.

---

## 🧰 Technologies & Tools Used

- **Language:** C#
- **IDE:** Xamarin Studio
- **Networking:** TCP & HTTP
- **Cryptography:** SHA-1 (for piece verification)
- **Testing Tools:**
  - **VirtualBox** with **Ubuntu** VMs (to simulate peers)
  - **OpenTracker** (BitTorrent tracker)
  - **Deluge** (external BitTorrent client)

---

## 🔧 Project Highlights

- Parsed `.torrent` files to extract metadata.
- Connected to a tracker server to retrieve a list of peers.
- Broke files into chunks and verified each piece using SHA-1 hashing.
- Simulated peer-to-peer behavior (seeder vs leecher).
- Managed file I/O for reading/writing pieces of the final file.
- Laid groundwork for multi-threaded support and piece selection algorithms.

---

## 🎯 Learning Objectives

The objective was to gain hands-on experience with:

- Peer-to-peer networking protocols
- Custom binary encodings
- Socket programming using TCP
- Data integrity via hashing
- Decentralized systems architecture

While not yet production-ready, this version forms a solid base for future improvements such as:

- Trackerless peer discovery (DHT)
- Advanced piece selection algorithms
- Full multi-threaded downloading

---

## 📂 Scope

BitTorrent is an ideal learning project as it spans multiple computer science domains: networking, security, systems design, and concurrency. The implementation here focuses on version 1.0 of the protocol, intended as a learning tool rather than a full client.

---

## 📎 References

- Official BitTorrent protocol specification
- OpenTracker (tracker server)
- Deluge (client reference)
- Various protocol analysis resources

---



