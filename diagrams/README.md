# Diagrams go here
[Router]
   │
   └── [Switch/AP]─── Laptop (LAN IP)
                     └── Phone (LAN IP)
                     └── Raspberry Pi (Wi-Fi IP)

LAN range: 192.168.4.0/24

Pi gets an IP from Wi-Fi (e.g., 192.168.4.50).

Guest devices: 192.168.4.96/27

IoT devices: 192.168.4.64/27

Save that image into diagrams/.
Screenshots of subnetting practice can go in captures/.