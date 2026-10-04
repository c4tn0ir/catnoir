# Linux Systems Debugging & Automation

Sanitized public engineering note.

## Scope

Multi-node Linux service operations where failures can cross:

- application code
- systemd state
- networking
- DNS
- TLS/protocol configuration
- APIs
- host-specific configuration

## Method

1. Confirm process/service state.
2. Check exact listeners and process ownership.
3. Verify local behavior before external behavior.
4. Compare DNS, routing, firewall, and protocol reachability.
5. Validate effective configuration.
6. Compare failing and known-good nodes.
7. Automate the final verification path.

## Technologies

Linux · systemd · SSH · Bash · Python · TCP/IP · DNS · REST APIs · service/runtime diagnostics
