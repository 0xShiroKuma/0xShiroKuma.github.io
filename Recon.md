# Network scan

## Nmap

Command exemple : 
```nmap -sS -A -T4 -p- -Pn -sV -sC -oX scan.xml X.X.X.X```

- -sS : TCP SYN port scan (Default)
- -A : Enables OS detection, version detection, script scanning, and traceroute
- -T4 : Aggressive (4) speeds scans; assumes you are on a reasonably fast and reliable network
- -oX : XML output
- -p- : Full TCP port scan
- -Pn : Disable Ping scanning
- -sV -sC : Scan using default safe scripts

```sudo nmap -sU --top-port 1000 -T4 -Pn -sV -sC -oX UDP_scan.xml X.X.X.X```
