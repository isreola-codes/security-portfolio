# TCP, UDP and ICMP

## TCP: the careful postman
TCP makes a connection with a three-way handshake:
1. SYN: "Hello, want to talk?"
2. SYN-ACK: "Yes! Do you hear me?"
3. ACK: "Yes, let's go."

TCP is reliable because it numbers the pieces and resends any that get lost.

## UDP: the speedy shouter
UDP is fast but not reliable. It is used for things like online video games and video calls, because a lost piece is only a tiny glitch.

## ICMP: the messenger
ICMP carries network messages, not my data. The ping command uses it.

## My ping test
I ran `ping -c 4 8.8.8.8`:
- 4 packets sent, 4 received, 0% packet loss
- Average round trip: about 34.6 ms

## Why this matters for security
Scanners like Nmap use these ideas to find out which ports are open and which devices are alive.
