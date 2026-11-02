# IP addressing and subnetting

## IP addresses
An IPv4 address has 4 numbers separated by dots, and each number is between 0 and 255. It has two parts: the network (the street) and the host (the house).

- **Private** addresses are used inside a home network, like 192.168.1.x.
- **Public** addresses are used on the whole internet.

## Subnet masks
The slash number, like /24, tells you how long the network part is. In a /24, the first 3 numbers are the street.

- A /24 has 256 addresses, but only 254 are usable, because the first and last are reserved.
- Every +1 on the slash divides the street in half.
- A /25 splits into two streets: .0 to .127 and .128 to .255.

## Same network or not?
Two devices are on the same network if they are in the same street. If not, they must talk through the router.

## Why this matters for security
When scanning a network, analysts use the slash number to decide how big an area to check. A /24 scans 254 devices, and a /16 scans around 65,000.
