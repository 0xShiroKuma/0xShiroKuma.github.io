# Web discovery

## Content discovery by brute force

### Tools 
- [**Rust**] [Feroxbuster](https://github.com/epi052/feroxbuster) A simple, fast, recursive content discovery tool written in Rust
- [**Shell**] [Byp4xx](https://github.com/lobuhi/byp4xx) A bash script to bypass "403 Forbidden" responses with well-known methods discussed in #bugbountytips.
- [**Go**] [Gobuster](https://github.com/OJ/gobuster) a tool used to brute-force:
  - URIs (directories and files) in web sites.
  - DNS subdomains (with wildcard support).
  - Virtual Host names on target web servers.
  - Open Amazon S3 buckets
  
## Subdomain discovery

### Tools
- [**Go**] [getallurls (gau)](https://github.com/lc/gau) fetches known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl for any given domain. For Subdomain-Enumeration.
- [**Online**] [Subdomainfinder](https://subdomainfinder.c99.nl/] a tool which performs an advanced scan over the specified domain and tries to find as many subdomains as possible. While scanning it also checks whether the domain is tunneling through CloudFlare.


## WebSite crawling

### Tools 
- [**Python**] [Photon](https://github.com/s0md3v/Photon) Incredibly fast crawler designed for OSINT. Photon can extract the following data while crawling: 
  - URLs
  - intel (emails, social media accounts, amazon buckets etc.)
  - Files
  - Secret keys...
- [**Go**] [GoSpider](https://github.com/jaeles-project/gospider) Fast web spider written, features:
  - Fast web crawling
  - Brute force and parse sitemap.xml
  - Parse robots.txt
  - Generate and verify link from JavaScript files
  - Link Finder
  - Find AWS-S3 from response source
  - Find subdomains from response source
  - Get URLs from Wayback Machine, Common Crawl, Virus Total, Alien Vault
  - Format output easy to Grep
  - Support Burp input
  - Crawl multiple sites in parallel
  - Random mobile/web User-Agent
  
  
