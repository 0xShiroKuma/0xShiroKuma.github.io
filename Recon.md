# Network scan

## Nmap

Service, OS detection, all ports, XML output : 
```nmap -sS -p- -A -T4 -oX scan.xml X.X.X.X```

- -sS : TCP SYN port scan (Default)
- -p- : Port scan all ports
- -A : Enables OS detection, version detection, script scanning, and traceroute
- -T4 : Aggressive (4) speeds scans; assumes you are on a reasonably fast and reliable network
- -oX : XML output
