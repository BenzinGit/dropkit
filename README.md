# dropkit
Lightweight file transfer toolkit for pentesting and CTF environments.
Designed for fast, flexible file delivery and exfiltration across Linux and Windows targets.
---

## Features
- File delivery (drop / dropw)
- File exfiltration (grab / grabw)
- Supports HTTP, fileless, raw TCP (netcat), and offline methods
- Automatic IP detection (tun0 / routing fallback)
- Copy-paste ready one-liners (clipboard support)

## Tools
| Tool  | Description |
| ------------- | ------------- |
| drop  | Linux file delivery  |
| grab  | Linux file exfiltration  |
| dropw  | Windows file delivery  |
| grabw  | Windows file exfiltration  |

## Requirements
- Linux attacker machine
- Python 3
- netcat

Optional:
- xclip
- uploadserver

