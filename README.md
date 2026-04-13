# dropkit

Lightweight file transfer toolkit for pentesting and CTF environments.
Designed for fast, flexible file delivery and exfiltration across Linux and Windows targets.

## Tools
| Tool  | Description |
| ------------- | ------------- |
| drop  | Linux file delivery  |
| grab  | Linux file exfiltration  |
| dropw  | Windows file delivery  |
| grabw  | Windows file exfiltration  |


## How to use
### Drop file (Linux target)
```bash
drop <file> [http|fileless|bash|encrypted|offline] [port]
```

Grab file (Linux target)
```bash
grab <outfile> [nc|http|offline] [port]
```


Drop file (Windows target)
```bash
dropw <file> [http|fileless|offline] [port]
```


Grab file (Windows target)
```bash
grabw <outfile> [nc|http|smb|offline] [port]
```

## Requirements
- Linux attacker machine
- Python 3
- netcat

Optional:
- xclip
- uploadserver

