# Ansible Role: bind9

## Public DNS Resolvers
- Cloudflare DNS (Block malware): https://developers.cloudflare.com/1.1.1.1/ip-addresses/
- Quad 9 DNS: https://quad9.net/

## How to generate a TSIG key?
```bash
tsig-keygen -a hmac-sha256
```
