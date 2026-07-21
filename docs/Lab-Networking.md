# Network Configuration

## Virtual Machines

- Windows 11
- Ubuntu
- Rocky Linux
- Kali Linux

---

## Network Adapters

### All Virtual machines

Adapter 1

- NAT

Adapter 2

- Internal Network

This gives the virtual machines internet access while also allowing them to communicate with eachother.

---

## IP Addresses

Each virtual machine was assigned its own static IP address. Windows was also assigned a subnet mask.

Each virtual machine pinged the other to test for successful connectivity.

---

## Lessons Learned

Network configuration made it so the virtual machines could communicate with eachother. This would be neccessary for future labs and projects involving things like Nmap and Wireshark. It would also be relevant for future incident response labs.
