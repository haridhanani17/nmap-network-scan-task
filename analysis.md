## Open Ports Analysis

### Device 1 - 192.168.1.1
- **22 (SSH):** Remote login, secure but must have strong passwords.
- **53 (DNS):** Open to resolve domain names, may be misused for amplification attacks.
- **80 (HTTP) and 443 (HTTPS):** Standard for web traffic; ensure HTTPS is enforced.

### Device 2 - 192.168.1.105
- **139, 445 (NetBIOS/SMB):** High-risk ports; used for file sharing. Must be firewalled or restricted.

## Security Risks
- Unused open ports can be entry points for attackers.
- Ports like 445 (SMB) are commonly targeted by malware.

## Recommendations
- Close unnecessary ports
- Use firewalls and access control
- Regularly scan and audit network
