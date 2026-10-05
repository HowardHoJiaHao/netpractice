# NetPractice

> 42 Common Core · Rank 04

*This project has been created as part of the 42 curriculum by hho-jia-*

**Description**

This project involves configuring small-scale networks to ensure seamless data flow between different interfaces and subnets. The primary goal is to master TCP/IP addressing and resolve common connectivity issues like routing loops.

**Instructions**

There are 10 levels to solve. My configuration for each level is in `level1.json` … `level10.json`.

Steps to run the exercise:
1. Download the file attached to the project’s page.
2. Extract the files in any folder.
3. In this folder, open the `index.html` file.
4. The training interface opens in your web browser.

Buttons available:
1. **Check again**: checks whether all my connections are correct
2. **Get my config**: downloads my configuration, which is submitted in this repository
3. **Next level / Complete!**: only appears when all connections are correct, to move on to the next level

**Resources**

I used Gemini to understand how networks, subnet masks and IP addresses work, including:

- **TCP/IP Addressing**: A unique numerical identifier assigned to every device on a network. It functions like a digital mailing address, ensuring data packets are routed to the correct destination without getting lost.
- **Subnet Mask**: A logical "boundary marker" that tells a device which part of its IP address belongs to the neighborhood (network) and which part belongs to the individual house (host). It essentially defines the size and limits of your local network.
- **Default Gateway**: The "border crossing" of your local network. It is the specific IP address (usually the router) that handles any traffic trying to leave your local area to reach a different network, such as a remote server or the internet.
- **Routers**: The intelligent navigators of the internet. They maintain a "map" called a routing table to determine the most efficient path for data to travel between entirely different networks.
- **Switches**: The internal coordinators of a single network. Unlike routers that connect different networks, switches connect devices within the same network. They use hardware addresses (MAC addresses) to send data directly to the specific port where a device is plugged in, reducing unnecessary noise.
