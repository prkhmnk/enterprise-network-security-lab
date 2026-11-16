# Project Requirements

## Business Context

The simulated company employs 50 people, with an initial on-site footprint of 10 client workstations and support for remote access. Four core business services are required: file, database, email, and web.

## Functional Requirements

- Document logical topology and service placement.
- Establish IPv4 subnets, static reservations, and dynamic client ranges.
- Define access paths for office and remote users.
- Identify the routing, name resolution, and address assignment services required.
- Specify backup, recovery, and maintenance assumptions.

## Security Requirements

- Separate user, server, management, and remote-access traffic where justified.
- Apply least-privilege rules to inter-segment traffic.
- Protect remote access with authenticated, encrypted connections.
- Document logging and validation expectations.

## Constraints and Assumptions

- This is a simulated environment, not a production deployment.
- A subset of endpoints will represent the planned 50-user capacity.
- Final implementation choices, resources, and constraints remain to be confirmed.
