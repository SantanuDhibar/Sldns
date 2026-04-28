# Sldns — SlowDNS Manager

A one-click SlowDNS (DNSTT) server installation and management menu script.

## One-Click Install

Run the following command as **root** on your server:

```bash
bash <(curl -s https://raw.githubusercontent.com/SantanuDhibar/Sldns/main/menu-slowdns.sh)
```

Or with `wget`:

```bash
bash <(wget -qO- https://raw.githubusercontent.com/SantanuDhibar/Sldns/main/menu-slowdns.sh)
```

## Features

- **Install SlowDNS** — downloads, builds, and configures a DNSTT server with your nameserver
- **Status** — view the current public key, nameserver, port, and running status
- **Restart** — restart the DNSTT service
- **Stop** — stop the DNSTT service
- **Change Port** — switch the forwarding port between 22 (SSH), 80 (HTTP), and 443 (HTTPS)
- **Uninstall** — completely remove SlowDNS and all related files

## Requirements

- Debian / Ubuntu-based Linux server
- Root access
- A nameserver (NS record) pointing to your server's IP

## Credits

- [SantanuDhibar/Sldns](https://github.com/SantanuDhibar/Sldns)
- [bamsoftware/dnstt](https://www.bamsoftware.com/git/dnstt.git)
