# Network Configs

Configuration files for the London DC core network infrastructure.

## Structure

- `configs/` — Device configurations, ACLs, and policies
  - `core-sw01.cfg` - Core switch 01 (VLANs, SVIs, management)
  - `acl-vlan10.cfg` - Management VLAN access control list
  - `qos-policy.cfg` - WAN edge QoS policy (voice, video, network-control)
  - `ntp.cfg` - NTP configuration with authentication

## Branching Conventions

- `main` - Production-ready configs
- `feature/*` - New features or config additions
- `hotfix/*` - Urgent production fixes
