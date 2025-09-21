# CIDR <-> mask conversions, usable hosts, and splits.

Example 1: /24 to /26 splits

/24 = 255.255.255.0 → 256 total IPs (254 usable).

Split into /26 = 255.255.255.192 → 64 total IPs (62 usable).

Subnets:

192.168.4.0 – 192.168.4.63

192.168.4.64 – 192.168.4.127

192.168.4.128 – 192.168.4.191

192.168.4.192 – 192.168.4.255

Example 2: /24 → /28

/28 = 255.255.255.240 → 16 total (14 usable).

Splits into 16 blocks.

Small LAN plan (LAN/IoT/Guest):

LAN: 192.168.4.0/26 → 62 usable (computers, laptops).

IoT: 192.168.4.64/27 → 30 usable (smart plugs, cameras).

Guest: 192.168.4.96/27 → 30 usable (visitors Wi-Fi).