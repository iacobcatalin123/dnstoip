#  dnstoip
For when you need to convert a lot of dns servers to ips.

## Usage

Assume you have dns.txt with 100 results.
```bash
dnstoip dns.txt | sort | uniq | wc -l 
```
will return 15 results so you can run nmap on them and never bother scanning the same host a milion times
