# Central URL/IP tables for OPNsense

## Purpose
This repository provides centrally managed IP lists used as trusted sources for OPNsense firewall deployments.  
By hosting these lists in one place and referencing them via URL Tables, we can:
- Ensure consistent network policies across multiple appliances  
- Minimize maintenance effort when IP ranges or RFC definitions change  
- Automate updates by linking OPNsense aliases directly to these lists  
- Improve security and transparency through version-controlled list management

Each file in this repository defines a specific category of IP networks, such as private, reserved, special-purpose or other operationally relevant ranges.

---

## Usage in OPNsense

You can import any list from this repository into OPNsense as a URL Table (IPs) or a URL Table in JSON format (IPs).
Please refer to the official OPNsense documentation for instructions on how to use these lists: [OPNsense documentation – Aliases](https://docs.opnsense.org/manual/aliases.html)

---

## File list
| File | Description |
|------|--------------|
| `ipv4_private_reserved_special.json` | Contains all private, reserved and special-purpose IPv4 networks (IANA + RFCs) |

---

© 2025 – BRAUNE GmbH
