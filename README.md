*This project has been created as part of the 42 curriculum by [tfilipe-].*

# netpractice_42

## Description

NetPractice is a system administration and networking exercise focused on understanding and configuring TCP/IP addressing. The goal is to solve 10 increasingly complex networking problems by correctly configuring IP addresses, subnet masks, routing tables, and network interfaces to establish proper communication between hosts.

This project provides hands-on practice with fundamental networking concepts including subnetting, routing, and network topology configuration. Each level presents a different network scenario that must be properly configured to allow devices to communicate with each other.

## Instructions

### Running the Training Interface

1. Open the training interface by accessing the provided web interface (typically `index.html` in a browser)
2. Load each level from the `Levels/` directory (level1.json through level10.json)
3. Configure the network parameters:
   - IP addresses for network interfaces
   - Subnet masks
   - Default gateways
   - Routing table entries
4. Test your configuration using the built-in validation tools
5. Once a level is solved, export the configuration

### Exporting Configurations

- After successfully completing each level, export the configuration file
- Save the exported file with the appropriate level name
- Ensure the configuration meets all connectivity requirements before exporting

### Submission Requirements

**For evaluation, you must place 10 exported configuration files (one per level) at the repository root.** These files should be named according to the level they correspond to (e.g., `level1.json`, `level2.json`, etc., through `level10.json`).

## Resources

### Networking Concepts Studied

This project covers the following fundamental networking concepts:

- **TCP/IP Addressing**: Understanding IPv4 address structure and assignment
- **Subnet Masks**: Calculating network and host portions of IP addresses using CIDR notation
- **Default Gateway**: Configuring routers as exit points for network traffic
- **Routers**: Understanding Layer 3 routing and packet forwarding
- **Switches**: Layer 2 device behavior and network segmentation
- **OSI Layers**: Focus on Layer 2 (Data Link) and Layer 3 (Network)
- **Routing Tables**: Static route configuration and next-hop determination
- **Network Topology**: Understanding how devices interconnect in a network
- **Broadcast vs. Unicast**: Traffic patterns and address types

### Documentation and References

- **Subnet Mask Tutorial**: [YouTube - Subnet Mask Explanation](https://www.youtube.com/watch?v=s_Ntt6eTn94)
- **Subnet Reference Sheet**: [Aelius Subnet Sheet](https://www.aelius.com/njh/subnet_sheet.html)
- **NetPractice Guide**: [GibbonTech NetPractice Guide](https://www.gibbontech.com/ecole42/netpractice/index.html)
- Official IPv4 addressing documentation (RFCs 791, 950)
- TCP/IP networking fundamentals and subnetting guides

### AI Usage

AI assistance was used in this project for the following tasks:

- **Concept clarification**: Understanding subnetting calculations and CIDR notation
- **Resource compilation**: Gathering and organizing relevant networking references
