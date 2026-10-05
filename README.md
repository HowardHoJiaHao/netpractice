# NetPractice

> 42 Common Core · Rank 04

*This project has been created as part of the 42 curriculum by hho-jia-*

## Introduction
NetPractice is a 42 project that introduces computer networking. It is a series of 10 exercises in a web-based training interface: each level shows a small network of hosts, switches, routers and sometimes the Internet, and some of the settings (IP addresses, subnet masks and routing tables) are missing or wrong.

The goal of each level is to configure these small-scale networks so that data flows between the right interfaces and subnets. The primary aim is to master TCP/IP addressing and to resolve common connectivity issues, such as overlapping subnets and routing loops.

## Levels
My configuration for each level is in `level1.json` … `level10.json`.

| Level | Network | Topics |
|:---:|---|---|
| 1 | Two pairs of hosts, each pair linked directly | IP addresses in the same network |
| 2 | Two pairs of hosts with set subnet masks | Subnet masks (e.g. `/27`) and which addresses they allow |
| 3 | Three hosts connected by a switch | One subnet (`/25`) shared by every host on the switch |
| 4 | Hosts, a switch and a router | A router interface inside the hosts' subnet (`/26`) |
| 5 | Two hosts on different networks joined by a router | Routing tables, default routes and gateways |
| 6 | A host reaching the Internet through a router | Default route out, and a route back from the Internet |
| 7 | Two hosts behind a chain of two routers | Splitting one network into non-overlapping `/26` subnets |
| 8 | Hosts behind two routers, connected to the Internet | Small `/28` subnets and routes in both directions |
| 9 | Four hosts, two routers and the Internet | Mixed subnet sizes and one route per network |
| 10 | Four hosts, two routers and the Internet | Fitting `/25`, `/26`, `/27` and `/30` subnets together without overlaps |

## How to use
1. Download the file attached to the project's page on the 42 intranet.
2. Extract the files in any folder.
3. In this folder, open the `index.html` file.
4. The training interface opens in your web browser. Enter your 42 login when asked, because the levels are generated from it.

Buttons available:
1. **Check again**: checks whether all the connections are correct
2. **Get my config**: downloads the current configuration (the `levelN.json` files in this repository)
3. **Next level / Complete!**: only appears when all connections are correct, to move on to the next level

## Resources
I used Gemini to understand how networks, subnet masks and IP addresses work, including:

- **TCP/IP Addressing**: A unique numerical identifier assigned to every device on a network. It works like a digital mailing address, making sure data packets are routed to the correct destination without getting lost.
- **Subnet Mask**: A logical "boundary marker" that tells a device which part of its IP address belongs to the neighbourhood (network) and which part belongs to the individual house (host). It defines the size and limits of the local network.
- **Default Gateway**: The "border crossing" of the local network. It is the IP address (usually the router) that handles any traffic leaving the local network to reach a different one, such as a remote server or the Internet.
- **Routers**: The navigators of the Internet. They keep a "map" called a routing table to decide the path data takes between different networks.
- **Switches**: The internal coordinators of a single network. Unlike routers, which connect different networks, switches connect devices within the same network. They use hardware (MAC) addresses to send data directly to the port where a device is plugged in.

## Clone
Clone the repository:
```bash
git clone https://github.com/HowardHoJiaHao/netpractice.git
```
