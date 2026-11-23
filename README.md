*This project has been created as part of the 42 curriculum by jabuleje.*

# NetPractice

## Description

NetPractice is a practical networking project from the 42 curriculum designed to introduce the fundamentals of computer networking.

The main objective is to understand how devices communicate within a network and how to configure IP addressing and routing to establish successful connections between different devices.

Through 10 progressive networking levels, the project introduces different network configurations and challenges involving computers, routers, switches, and network interfaces.

The exercises focus on identifying and solving network configuration problems by correctly assigning IP addresses, subnet masks, and default gateways.

## Networking Concepts

Throughout this project, the following networking concepts are studied and applied:

- **TCP/IP addressing:** Understanding IPv4 addresses and network communication.
- **Subnet masks:** Identifying network and host portions of IP addresses.
- **CIDR notation:** Understanding network prefixes and address ranges.
- **Default gateways:** Configuring the path used to reach devices outside the local network.
- **Routers:** Connecting different networks and forwarding packets between them.
- **Switches:** Connecting devices within the same local network.
- **Network interfaces:** Understanding how devices connect to different networks.
- **OSI model:** Understanding the different layers involved in network communication.
- **TCP and UDP:** Understanding the transport protocols and their roles.
- **Routing:** Understanding how packets travel between different networks.

## Instructions

### 1. Running the training interface

Clone the repository:

```bash
git clone <repository-url>
cd NetPractice
```

Make the execution script executable:

```bash
chmod +x run.sh
```

Launch the training interface:

```bash
./run.sh
```

Follow the instructions provided by the script to open the NetPractice training environment in your browser.

### 2. Completing the exercises

The project consists of 10 networking levels.

For each level:

1. Analyze the network topology.
2. Identify the configuration errors.
3. Configure the IP addresses, subnet masks and default gateways.
4. Verify that the devices can communicate correctly.
5. Export the completed configuration.

### 3. Exporting configurations

Once a level has been successfully completed, use the export functionality available in the training interface to download its configuration file.

Repeat this process for all 10 levels.

### 4. Submission requirements

The repository must contain **10 exported configuration files**, one for each completed level.

All exported configuration files must be placed directly at the root of the Git repository.

Example:

```text
NetPractice/
├── README.md
├── run.sh
├── level1.json
├── level2.json
├── level3.json
├── level4.json
├── level5.json
├── level6.json
├── level7.json
├── level8.json
├── level9.json
└── level10.json
```

Make sure all 10 configurations are exported and included before submitting the project.

## Resources

The following resources were used to understand and practice the networking concepts covered in this project.

### Documentation and references

- [MDN - TCP/IP](https://developer.mozilla.org/en-US/docs/Glossary/TCP)
- [Cloudflare - What is an IP address?](https://www.cloudflare.com/learning/network-layer/what-is-an-ip-address/)
- [Cloudflare - What is a subnet?](https://www.cloudflare.com/learning/network-layer/what-is-a-subnet/)
- [Direccionamiento IP: IPv4, IPv6, clases y tipos de redes](https://www.youtube.com/watch?v=r6MN9Bt71jA)
- [Subnetting: Divide y organiza tus redes desde cero](https://www.youtube.com/watch?v=0GXDPAqrsA8&t=992s)

### AI Usage

AI tools, including ChatGPT, were used as learning and support resources throughout the project.

They were used for:

- Clarifying networking concepts such as IPv4 addressing, subnet masks, CIDR notation and default gateways.
- Understanding how routers connect different networks and forward packets.

AI was used as a learning aid.