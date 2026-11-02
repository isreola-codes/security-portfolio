# The OSI and TCP/IP models

Data travels through layers, like a gift that is written, wrapped, addressed and delivered. There are two models: OSI, with 7 layers, and TCP/IP, with 4 layers.

- **Application:** the message itself, or the order.
- **Transport:** chops the message into numbered pieces and checks they arrive. TCP is the protocol that does this.
- **Network:** puts the address on each piece. (TCP/IP calls this the Internet layer.)
- **Physical:** the actual carrying, like cables and Wi-Fi radio waves.

## Why this matters for security
When something goes wrong, an analyst asks: "Which layer is the problem?"
- A cut cable is a Physical problem.
- A fake login page is an Application problem.

## OSI layers, bottom to top
Physical, Data link, Network, Transport, Session, Presentation, Application

Memory phrase: **P**lease **D**o **N**ot **T**hrow **S**ausage **P**izza **A**way
