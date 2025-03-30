# Networking Security Lab (Cisco Packet Tracer)

## Brief Objective
The objective of this project was to establish a strong foundation in basic networking skills, providing hands-on experience in managing and securing a network environment. This setup allowed for the exploration of fundamental networking concepts, technical knowledge in device configuration, and an understanding of network security in a controlled lab environment using Cisco Packet Tracer.

## Skills Learned
- Network Security
- Networking Configuration
- Firewall Security Management

## Tools Used
- Cisco Packet Tracer

## Steps

### 1. Network Topology Setup
- Designed and implemented a structured network topology using Cisco Packet Tracer.
- Included devices such as routers, switches, access points, firewalls, and client devices.

### 2. Basic Network Configuration
- Implemented network segmentation using the `dhcp pool` command.
- Assigned IP addresses to clients based on connection type (wired vs. wireless).
- Ensured isolation between networks to enhance security in case of a wireless breach.

### 3. Wireless Router Configuration
- Configured the wireless router with security settings to prevent unauthorized access.
- Established a stable and secure connection for authorized devices.

### 4. Printer Configuration
- Assigned a static IP address to the network printer.
- Ensured that the printer’s IP remained unchanged to prevent connection issues.
- Reserved an IP address outside the DHCP pool to avoid conflicts.

### 5. DHCP Server Configuration
- Disabled DHCP service on the router.
- Configured DHCP on the firewall for centralized management.
- Set the DHCP pool’s starting IP address to `192.168.1.102` to avoid conflicts with reserved addresses.

### 6. DNS Configuration
- Configured a resource record on the DNS server (`192.168.1.254`).
- Enabled internet access for client devices by resolving domain names.

### 7. Access Point Configuration
- Deployed an additional access point to extend wireless coverage.
- Configured WPA2-PSK authentication to secure wireless connectivity.
- Ensured mobile devices (tablet and smartphone) could connect seamlessly.

### 8. Firewall Configuration for SSH Access
- Configured firewall parameters via CLI:
  - Set hostname
  - Assigned passwords and usernames
  - Configured time settings
- Enabled future remote SSH access for secure firewall management.

### 9. Network Zone Security Implementation
- Assigned different security levels to network zones:
  - **Internal Network** (trusted): Highest security level.
  - **DMZ (Demilitarized Zone)** (partially trusted): Medium security level.
  - **Untrusted Zone** (external users): Lowest security level.
- Configured security levels through CLI to enforce network segregation.

### 10. Remote SSH Configuration
- Enabled secure remote administration for firewall management.
- Used the AAA (Authentication, Authorization, and Accounting) protocol.
- Generated RSA key pairs to ensure encrypted and authenticated access.
