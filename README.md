# Smart Home Networking

## Table of Contents

- [Networking Importance](#networking-importance)
- [Architecture Diagram](#architecture-diagram)
- [Services Used for Smart Home](#services-used-for-smart-home)
- [Flowchart of Smart Home](#flowchart-of-smart-home)
- [Routing Algorithm Simulation](#routing-algorithm-simulation)
- [CRC (Cyclic Redundancy Check)](#crc-cyclic-redundancy-check)

## Networking Importance

The significance of networking in smart homes is underscored by statistical trends:

- Global consumer spending on smart home systems is projected to surpass $170 billion by 2025 (Strategy Analytics).
 ![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/b07e8184-8ed2-44cf-8569-13e2f39769ad)

- Asia-Pacific is anticipated to emerge as the largest smart home market by 2023 (Strategy Analytics).
- ![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/205a1dbe-e330-49c5-96f3-9d64328026c2)


## Architecture Diagram for connect IoT devices

![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/afb93a50-711a-48a9-9732-69d62315cf0d)

## Services Used for Smart Home
![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/879fd414-6a33-4190-b747-c400cf457dd2)

1. **Email Server:**
   - OSI Layer: Application (Layer 7)
   - Explanation: Email services operate at the application layer, facilitating communication between applications and users.

2. **VLAN (Virtual Local Area Network):**
   - OSI Layer: Data Link (Layer 2) and Network (Layer 3)
   - Explanation: VLANs encompass both layer 2 (segmentation) and layer 3 (routing) functionalities.

3. **DNS (Domain Name System):**
   - OSI Layer: Application (Layer 7)
   - Explanation: DNS operates at the application layer, translating human-readable domain names to IP addresses.

4. **FTP Network:**
   - OSI Layer: Application (Layer 7)
   - Explanation: FTP operates at the application layer, facilitating file transfer between devices.
```bash
ipconfig 
ftp 192.168.0.40
```

5. **HTTP Server:**
   - OSI Layer: Application (Layer 7)
   - Explanation: HTTP, used for hosting web-based interfaces, operates at the application layer.

6. **DHCP (Dynamic Host Configuration Protocol):**
   - OSI Layer: Application (Layer 7) and Network (Layer 3)
   - Explanation: DHCP operates at the application layer for configuration and uses the network layer (IP) for assigning dynamic IP addresses.

7. **IoT (Internet of Things):**
   - OSI Layer: Typically Data Link and Network layers
   - Explanation: IoT devices may use various communication protocols, spanning multiple OSI layers.

8. **AAA (Authentication, Authorization, and Accounting):**
   - OSI Layer: Presentation (Layer 6) and Application (Layer 7)
   - Explanation: AAA services operate at the presentation and application layers, ensuring secure network access.

## Flowchart of Smart Home

![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/195f3901-5dff-49a8-ba3d-0fba5346b759)
## Routing Algorithm Simulation

Simulate the routing algorithm considering multiple routers:
```bash
ping 10.0.02
tracert 10.0.0.2
```
![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/d045b103-3456-459d-9ec9-81e36ee92c83)
- **Distance Vector**
  - Utilize RIP (Routing Information Protocol) with the criterion of the minimum number of hops.
![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/1b675941-10a5-48bb-a099-142e9e2da417)

Visit the link [RIP Protocol Configuration Guide with Examples](https://www.computernetworkingnotes.com/ccna-study-guide/rip-protocol-configuration-guide-with-examples.html).

## CRC (Cyclic Redundancy Check)

To maintain data integrity within the smart home application, CRC is employed. Simulate CRC for any data using the following command:
![image](https://github.com/Leonallr10/smart-home-CISCO-pkt-/assets/118210551/fb4ae2a6-b7cd-4094-bba0-998f470c12c8)

```bash
sh interfaces | in up|CRC


