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

## Interview Questions
1. What is a firewall?
2. Difference between stateful and stateless firewall?
3. What are inbound and outbound rules?
4. How does UFW simplify firewall management?
5. Why block port 23 (Telnet)?
6. What are common firewall mistakes?
7. How does a firewall improve network security?
8. What is NAT in firewalls?
