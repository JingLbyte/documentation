# Network Topology Overview

**Network Topology** defines how devices in a computer network are arranged. Various types, such as bus, star, and mesh, influence data flow and connectivity. It impacts performance, scalability, fault tolerance, and resource sharing. Understanding topology is crucial for efficient network management, security, and cost optimization. Choosing the right topology is essential for building a robust and efficient network infrastructure.

## Network Topology

| Subnet        | VLAN 10       | VLAN 20       | VLAN 30     | VLAN 40 | 
| ------------- | :-------------: | :-------------: | :-------------: | :-------------: |
| Location:     | Central Server  | Sales & Marketing | R&D | Expansion |
| Range:        | 10.10.10.0/24   | 10.10.20.0/24   | 10.10.30.0/24   | 10.10.40.0/24 |
| Subnet ID:    | 10.10.10.0      | 10.10.20.0      | 10.10.30.0      | 10.10.40.0 |
| First IP:     | 10.10.10.1      | 10.10.20.1      | 10.10.30.1      | 10.10.40.1 |
| Last IP:      | 10.10.10.254    | 10.10.20.254    | 10.10.30.254    | 10.10.40.254 |
| Broadcat IP:  | 10.10.10.255    | 10.10.20.255    | 10.10.30.255    | 10.10.40.255 |

### Subnet Details:

- **Subnet Range:** 10.10.0.0/18
- **Subnet ID:** 10.10.0.0
- **First Usable IP:** 10.10.0.1
- **Last Usable IP:** 10.10.63.254
- **Broadcast IP:** 10.10.63.255

### Host Distribution:

- **Total Hosts:** 16,384
- **Usable Hosts:** 16,382

### Subnet Mask Information:

- **Subnet Mask:** 255.255.192.0
- **Wildcard Mask:** 0.0.63.255
- **Binary Subnet Mask:** 11111111.11111111.11000000.00000000

### IP Class and CIDR:

- **IP Class:** B
- **CIDR Notation:** /18

### IP Type:

- **IP Type:** Private

### Summary:

The company's network operates on the private IP range 10.10.0.0/18, providing a total of 16,384 hosts with a usable range from 10.10.0.1 to 10.10.63.254. The subnet mask is 255.255.192.0 (CIDR /18), indicating a Class B network. This setup allows for 16,382 usable hosts within the private IP space.

For further details, refer to the following:

- **IP Address:** 10.10.10.1
- **Network Address:** 10.10.0.0
- **Broadcast Address:** 10.10.63.255
- **Subnet Mask:** 255.255.192.0
- **CIDR Notation:** /18
---------------------------------













