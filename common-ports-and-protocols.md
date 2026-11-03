# Common ports and protocols

An IP address is the building's address. A port is a numbered door on that building. One server can run many services, and each one waits at its own port.

| Port | Protocol | What it does | Security note |
|---|---|---|---|
| 21 | FTP | Moves files between computers | Plain text, unsafe |
| 22 | SSH | Secure, encrypted remote control | Safe replacement for Telnet |
| 23 | Telnet | Old remote control | Sends passwords as plain text |
| 25 | SMTP | Sends email | Should be locked down |
| 53 | DNS | The internet's phone book | Used constantly |
| 80 | HTTP | Websites in plain text | Anyone watching can read it |
| 443 | HTTPS | Encrypted websites | Safe |
| 445 | SMB | Windows file sharing | A common target for attackers |
| 3389 | RDP | Windows Remote Desktop | A common target for attackers |

## Why this matters for security
Tools like Nmap check which ports are open. Every open port is a place an attacker might try, so analysts ask: "Does this server need that port open, and is it locked properly?"
