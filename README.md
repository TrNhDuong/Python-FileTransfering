# Socket File Transfer Project (TCP & UDP Variants)

This project is a **course assignment for the subject _Computer Networks_** at  
**University of Science – VNU-HCM (HCMUS)**.

It demonstrates how to transfer a file from server to client using **Python sockets**, through multiple versions:  
- **TCP** (stream-based reliable transfer)  
- **UDP** (connectionless, best-effort)  
- **UDP with parallel segment sending** (manual reliability / concurrency)

---

## Project Features

✅ Implemented three socket-based transfer models:
- **Version 1 – TCP:** Reliable transmission using Python's TCP sockets.
- **Version 2 – UDP:** Faster but less reliable transmission using UDP sockets.
- **Version 3 – UDP Parallel:** UDP file sending where multiple chunks are sent in parallel (threaded), simulating optimized or segmented transfer.

✅ Highlights:
- Simple interface and file-based transfer
- No external libraries (pure `socket`, `threading`, etc.)
- Cross-platform
- Well-separated modules for each version

---

## Technologies Used

- **Language:** Python 3.x
- **Libraries:** socket, os, threading, time
- **No external dependencies**

---


