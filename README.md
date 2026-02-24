# DHCP-config-lab
This documentation covers the full setup and configuration of a DHCP (Dynamic Host Configuration Protocol) server on Windows Server 2022 inside a VMware Workstation lab environment. The goal was to simulate a functional internal network with automated IP addressing, reservations, exclusions, and DNS integration.
Tasks Completed
 1. DHCP Installation
- Installed the DHCP Server role on Windows Server 2022.
- Completed post‑deployment configuration.
- Authorized the DHCP server in Active Directory.
2. DNS Configuration
- Configured DNS server settings to integrate with DHCP.
- Ensured clients receive correct DNS information through DHCP options.
3. Scope Creation
- Created a new scope named **Internal Network** (Scope 1).
- Defined the IP address range for the scope.
- Configured subnet mask and default gateway.
- Added scope description for clarity.
4. Exclusions and Delay
- Added exclusion ranges to prevent certain IPs from being assigned.
- Configured DHCP delay to prioritize specific DHCP servers if needed.
5. Lease Duration
- Set the DHCP lease duration to **8 hours** to simulate a dynamic lab environment.
6. Reservations
- Created a reservation using a client’s MAC address.
- Configured reservation details (IP, name, description).
- Left the reservation **inactive** to demonstrate configuration without activation.
7. Scope Content Review
- Verified scope properties, options, and address pool.
- Confirmed the IP range, exclusions, and active leases.
8. Screenshots
All screenshots documenting each step are included in the `/screenshots` folder.
9. Purpose
This project demonstrates hands‑on experience configuring DHCP and DNS services in a Windows Server 2022 environment, including scope management, reservations, exclusions, and lease settings.
