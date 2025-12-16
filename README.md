*This project has been created as part of the 42 curriculum by tfilipe-*

## Description

- NetPractice is a system administration and networking exercise focused on understanding and configuring TCP/IP addressing.
- The goal is to solve 10 increasingly complex networking problems by correctly configuring IP addresses, subnet masks, routing tables, and network interfaces to establish proper communication between hosts.
- This project provides hands-on practice with fundamental networking concepts including subnetting, routing, and network topology configuration.
- Each level presents a different network scenario that must be properly configured to allow devices to communicate with each other.

## Instructions

### Running the Training Interface

1. First, download the repository.
2. Then, extract the files in whatever folder you want.
3. In this folder, run the `index.html` file.
4. You can practice if you input your login in the field, using your personal configuration.
5. Or you can use the ’evaluation’ tab for a random configuration, suitable for evaluations.
6. There are 10 levels available for training. For each level, a non-functioning network diagram appears.
7. Configure the network parameters:
   - IP addresses for network interfaces
   - Subnet masks
   - Default gateways
   - Routing table entries
8. Test your configuration using the `Check again`.

   - At the bottom of the page, you will see logs. They can be helpful to understand why your configuration is wrong, for example, if a gateway is missing or an IP address is invalid.
   - When you have successfully completed a level, click `Get my config` to export the configuration.
   - Then a new button will appear. Click on this button to get to the next level `Next level`
9. Complete 10 levels to finish.
10. For evaluation, you must place 10 exported configuration files (one per level) at the repository root. These files should be named according to the level they correspond to (e.g., `level1.json`, `level2.json`, etc., through `level10.json`).


## Resources

### Networking Concepts Studied

This project covers the following fundamental networking concepts:

- **TCP/IP Addressing**: Understanding IPv4 address structure and assignment
- **Subnet Masks**: Calculating network and host portions of IP addresses using CIDR notation
- **Default Gateway**: Configuring routers as exit points for network traffic
- **Routers**: Understanding Layer 3 routing and packet forwarding
- **Switches**: Layer 2 device behavior and network segmentation
- **OSI Layers**: Understanding where is the problem 

### Documentation and References

- **Subnet Mask Tutorial**: [YouTube - Subnet Mask Explanation](https://www.youtube.com/watch?v=s_Ntt6eTn94)
- **Subnet Reference Sheet**: [Aelius Subnet Sheet](https://www.aelius.com/njh/subnet_sheet.html)
- **NetPractice Guide**: [GibbonTech NetPractice Guide](https://www.gibbontech.com/ecole42/netpractice/index.html)
- **Official IPv4 addressing**: [What is Internet Protocol Version 4](https://www.geeksforgeeks.org/computer-networks/what-is-ipv4/)
- **TCP/IP**: [Alpha Brains Courses](https://youtube.com/playlist?list=PLEoK7C0HvDQnkx_yBfuFCvF7ecfCKiWA_&si=s7_gRsubd07I4hDu) 

### AI Usage

AI assistance was used in this project for the following tasks:

- **Concept clarification**: Understanding subnetting calculations and CIDR notation
- **OSY Layers**: [Understanding how is the OSI Layers](https://chatgpt.com/share/69416bec-fdc4-800d-afa3-455edda42b5d)
