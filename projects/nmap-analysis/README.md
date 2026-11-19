# Nmap Scanning Lab

Scanned a local Windows test system (127.0.0.1) with Zenmap's Intense Scan to find listening ports and services.

## Findings
| Port | Service | Role |
|---|---|---|
| 135/tcp | Microsoft RPC | Windows service communication |
| 445/tcp | SMB | File sharing |

Other scanned ports were closed.

## Analysis
Open ports aren't vulnerabilities by themselves; risk depends on configuration, version, exposure, and patching. RPC and SMB are common attack targets when exposed or unpatched.

## Hardening
- Disable unneeded services
- Limit RPC/SMB to trusted networks
- Block external access with firewalls
- Patch regularly
- Monitor for unexpected service changes

[← Back to all projects](../)
