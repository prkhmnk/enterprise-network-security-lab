# IP Addressing Plan

**Status:** Address space has not yet been assigned.

## Address Planning Requirements

Allocate RFC 1918 private IPv4 networks for appropriate internal segments. Record each subnet's purpose, prefix length, default gateway, DHCP scope, and reserved/static range.

| Segment | Network / Prefix | Gateway | Static / Reserved Range | DHCP Range |
|---|---|---|---|---|
| Clients | TBD | TBD | TBD | TBD |
| Servers | TBD | TBD | TBD | TBD |
| Management | TBD | TBD | TBD | TBD |
| Remote Access | TBD | TBD | TBD | TBD |

## Allocation Principles

- Assign predictable IP addresses to infrastructure and servers.
- Use DHCP for ordinary workstations unless a specific use case requires otherwise.
- Reserve capacity for growth without confusing employee count with simultaneously deployed virtual machines.
- Document DNS resolvers, network boundaries, and any translation policies.
