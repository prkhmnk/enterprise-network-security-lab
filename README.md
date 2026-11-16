# Enterprise Network Infrastructure & Security

An independent, simulated enterprise infrastructure project focused on designing, implementing, securing, and validating a network for a fictional organization.

> **Status:** Planning and design. No deployment or security validation is claimed yet.

## Business Scenario

A fictional organization has 50 employees, including office-based and remote users. Its initial office environment contains 10 client workstations. The organization requires four business services: file sharing, databases, email, and web applications.

## Project Objectives

- Design a scalable network topology and an IPv4 addressing plan.
- Allocate static addresses for infrastructure and dynamic address pools for clients.
- Plan secure segmentation, routing, and remote access.
- Implement infrastructure incrementally in an isolated lab environment.
- Validate allowed and denied connectivity and document the evidence.

## Scope

**Planned:** network architecture, IP addressing, server placement, firewall policies, remote-access design, implementation, and verification.

**Not yet implemented:** all technical configurations and validation tests.

## Roadmap

1. Requirements and network design
2. Infrastructure deployment
3. Network security controls
4. Security validation and troubleshooting
5. Documentation and publication

## Repository Structure

- `docs/` — requirements, design decisions, addressing, security, and validation plans
- `diagrams/` — topology diagrams (to be added)
- `configs/` — sanitized infrastructure configurations (to be added)
- `scripts/` — deployment and validation scripts (to be added)
- `evidence/` — sanitized test outputs and screenshots (to be added)

## Environment

Candidate technologies include VMware Workstation Pro, pfSense, Windows Server, Linux, and Cisco Packet Tracer. Final technology choices will be documented as implementation progresses.

## Security and Ethics

This is a fictional organization and an isolated, authorized lab. No real organization or customer infrastructure is represented. Do not commit credentials, private keys, tokens, or sensitive internal configuration details.
