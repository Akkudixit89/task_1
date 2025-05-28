# Task_1
**OBJECTIVE** : Learn to discover open ports on devices in your local network to
understand network exposure.<br>
**TOOLS** : Nmap
# Mentioning  targets in Nmap:
1. Single IP Address or Hostname
2. Multiple IPs or Hostnames
3. IP Range (Dash Notation)
4. CIDR Notation (Subnet Scan)
5. Input from a File (Target List)

# SCAN TECHNIQUES
1. tcp connect scan (-sT)
2. tcp syn scan (-sS)
3. fin scan (-sF)
4. xmas scan (-sX)
5. null scan (-sN)
6. ping scan (-sP)
7. udp scan (-sU)
8. ack scan (-sA)

# Os detection
nmap -O 192.168.1.0/24
