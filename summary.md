# Firewall Task Summary

## Key Concepts
- **Firewall:** Security system that monitors and filters incoming and outgoing network traffic.
- **Inbound rules:** Control traffic coming **into** your system.
- **Outbound rules:** Control traffic going **out** from your system.
- **Stateful firewall:** Tracks the state of active connections.
- **Stateless firewall:** Inspects packets individually without context.

## Why block Telnet (23)?
Telnet sends data in plain text (no encryption). Hackers can easily capture usernames and passwords. Modern systems disable Telnet by default in favor of SSH.

## Common Firewall Mistakes
- Forgetting to allow SSH/Remote Desktop access (locking yourself out).
- Overly permissive rules (allowing all traffic).
- Not testing after applying rules.

