# 🔌 Network Devices
Network devices are hardware components that facilitate communication and data transfer within and across networks.

---

## 1️⃣ Endpoint Devices
These are the clients and servers at the ends of the network.

- Client: Sends requests (e.g., laptop, phone)

- Server: Responds to requests (e.g., web server, email server)

📱➡️💻
Client asks → Server answers

---

## 2️⃣ Server Devices
Specialized machines designed to handle multiple client requests efficiently.

**Examples**:

- FTP Server (file transfer)

- DHCP Server (IP assignment)

- Log Server, Syslog Server

⚙️ Note:
Servers need high-performance hardware (CPU, RAM, storage) to scale with user demands.

![EPSD Diagram](/ccna/Network-Fundamentals/images/EPSD-diagram.png)

---

## 3️⃣ NIC – Network Interface Card
A NIC enables a device to connect to a network and communicate with others.

- Wired NIC: Uses RJ45 Ethernet port

- Wireless NIC: Uses antenna or dongle for Wi-Fi connectivity

🌐 Found as internal (built-in) or external (USB dongle)

**Technical Role**:

Operates at both the Physical Layer and Data Link Layer of the OSI model

**Has two key addresses**:

- MAC Address: Physical (48-bit hexadecimal)

- IP Address: Logical (32-bit decimal for IPv4)

![NIC Diagram](/ccna/Network-Fundamentals/images/NIC-diagram.png)

---

## 4️⃣ Network Switch
Used to interconnect devices within a LAN.

**Types**:

- Layer 2 Switch: Works at the Data Link Layer, forwards frames based on MAC addresses

- Layer 3 Switch: Works at the Network Layer, routes traffic based on IP addresses (can perform basic routing)

![NS Diagram](/ccna/Network-Fundamentals/images/NS-diagram.png)