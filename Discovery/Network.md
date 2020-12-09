# Hosts/network scan

## Tools
### [**Multi language**] [Nmap](https://github.com/nmap/nmap)

TCP scan exemple : 
```nmap -sS -A -T4 -p- -Pn -sV -sC -oX scan.xml X.X.X.X```
- -sS : TCP SYN port scan (Default)
- -A : Enables OS detection, version detection, script scanning, and traceroute
- -T4 : Aggressive (4) speeds scans; assumes you are on a reasonably fast and reliable network
- -p- : Full TCP port scan
- -Pn : Disable Ping scanning
- -sV -sC : Scan using default safe scripts
- -oX : XML output


UDP scan exemple :
```sudo nmap -sU --top-port 1000 -T4 -Pn -sV -sC -oX UDP_scan.xml X.X.X.X```

  - -sU : UDP port scan
  --top-port 1000 : First 1000 top port
  - -T4 : Aggressive (4) speeds scans; assumes you are on a reasonably fast and reliable network
  - -Pn : Disable Ping scanning
  - -sV -sC : Scan using default safe scripts
  - -oX : XML output

Other usefull parameters : 
  - -iL targets.txt : Scan the given hosts in the "targets.txt" file

Beautify your nmap report :
- [**xlsx**] [nmap-bootstrap-xsl](https://github.com/honze-net/nmap-bootstrap-xsl) a Nmap XSL implementation with Bootstrap.

# DNS discovery

## Tools
- [**C**] [MassDNS](https://github.com/blechschmidt/massdns) MassDNS is a simple high-performance DNS stub resolver targeting those who seek to resolve a massive amount of domain names in the order of millions or even billions.
