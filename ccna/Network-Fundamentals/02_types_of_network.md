# 🌐 Types of Networks

---

## 1️⃣ Personal Area Network (PAN)
A PAN connects devices in a very small range — typically around a single person.

**Examples**:

- Smartphone hotspot

- Smartwatch connected to a phone via Bluetooth

📶 Range: Very short
📱 Use Case: Personal devices only

![PAN Diagram](/ccna/Network-Fundamentals/images/PAN-diagram.png)

---

## 2️⃣ Local Area Network (LAN)

A LAN connects multiple computers and devices within a limited area like a home, office, or school.

LAN can be wired, wireless, or a combination of both.

**How it works**:

- Wired LAN: Devices are connected via network switches and Ethernet cables

- Wireless LAN (WLAN): Devices connect via Wi-Fi access points, which are themselves wired to the switch or router

📶 Hybrid LAN:

A modern laptop connects via Wi-Fi (WLAN), while desktop PCs connect via Ethernet — both are part of the same LAN if connected to the same network switch or router.

🔗 Cables Used:

- UTP (up to 100m)

-  Fiber Optic (10–20km)

**Examples**:
- 6 computers — 3 wired via switch, 3 wireless via an AccessPoint — share files and printers within a private network.

**Advantages**:

- High-speed data transfer (especially wired)

- Centralized resource sharing (printers, storage)

- Can scale with both wired and wireless nodes

**Disadvantages**:

- Limited to one physical/geographic location

- Can suffer from performance or congestion as more users connect

![LAN Diagram](/ccna/Network-Fundamentals/images/LAN-diagram.png)

![LAN-WLAN Diagram](/ccna/Network-Fundamentals/images/LAN-WLAN-diagram.png)

---

## 3️⃣ Wireless Local Area Network (WLAN)
A WLAN is similar to LAN but uses wireless access points (Wi-Fi) to connect devices.

📡 Fixed access points, unlike PAN devices that move with users

Can be connected to:

- A LAN switch

- Internet router

**Advantages**:

- Wireless connectivity

- Flexible device mobility

- Extendable with multiple APs

**Disadvantages**:

- Susceptible to congestion

- May suffer performance drops in dense environments

![WLAN Diagram](/ccna/Network-Fundamentals/images/WLAN-diagram.png)

---

## 4️⃣ Metropolitan Area Network (MAN)
A MAN spans a larger area than a LAN but is smaller than a WAN. It typically connects multiple LANs across a city or metropolitan region.

**How it works**:

- Uses high-speed backbone technologies (like fiber optics)

- Managed by governments, telecoms, or large organizations

**Examples**:

- FM Radio broadcasting within a city (e.g., Mumbai FM not available in Pune)

- Train station networks in a metro area

- City-wide surveillance systems or university campus networks

🌐 Coverage:
Limited to a single metropolitan area – ideal for connecting offices or facilities across a city

**Advantages**:

- Broader reach than LAN

- Cost-effective for regional connectivity

- Faster and more secure than using public internet between locations

**Disadvantages**:

- Higher setup cost than LAN

- Requires centralized management

- Limited to urban areas

![MAN Diagram](/ccna/Network-Fundamentals/images/MAN-diagram.png)

---

## 5️⃣ Wide Area Network (WAN)
A WAN is a computer network that spans a large geographical area, connecting multiple LANs over long distances.

**How it works**:

- Uses telecommunication lines (like fiber, telephone lines) or radio waves

- Interconnects cities, countries, or even continents

- Requires routing protocols to manage data transfer between distant nodes

🌍 Example:
Your office in Delhi connects to your branch in Bangalore using a WAN link provided by an ISP.

# ⚡ Routing Protocols in WAN
Routing protocols determine the best path for data packets across large networks by evaluating:

- Latency (how fast)

- Hop count (how many stops)

- Bandwidth availability

- Link reliability

🧠 Analogy:
Like GPS choosing the fastest route during traffic, routing protocols (like OSPF, BGP) help routers decide the optimal path for sending data.

![WAN Diagram](/ccna/Network-Fundamentals/images/WAN-diagram.png)

**Key Components**:

- Multiple Office Locations: Delhi, Bangalore (India), New York (USA), London (UK), and Sydney (Australia)
- Individual LANs: Each office has its own local network with computers and systems
- Routers (R1-R5): Handle routing decisions at each location
- ISP Cloud: Central internet infrastructure managing global connectivity

**WAN Technologies Shown**:

- Fiber Optic Cables (red solid lines) - High-speed connections between major cities
- Satellite Links (blue dashed lines) - For remote or backup connections
- Routing Path (orange highlighted) - Shows actual data path from Delhi to Bangalore

**Routing Protocols**:

- OSPF - Calculates shortest paths within organizations
- BGP - Routes data between different ISPs and countries
- Decision Factors: Latency, hop count, bandwidth, and link reliability

---

## 🔁 NAT64 & NAT46

🧰 **What Is NAT**?

NAT (Network Address Translation) allows devices on a private network to communicate with external public networks (like the internet) by translating IP addresses.

🌐 NAT64: IPv6 → IPv4

NAT64 allows IPv6-only devices to talk to IPv4-only servers.

🧠 Analogy:

Imagine you're speaking French (IPv6), and the server only understands English (IPv4). NAT64 is like a translator that helps both sides understand each other.

**Examples**:

- A smartphone on an IPv6-only mobile network accesses an old IPv4-only website

- NAT64 translates requests and responses in between

![NAT64 Diagram](/ccna/Network-Fundamentals/images/NAT64-diagram.png)

---

🔁 NAT46: IPv4 → IPv6

NAT46 allows IPv4-only clients to access IPv6-only resources.

🔄 Analogy:

Like using a universal adapter for a power plug when traveling — the plug (IPv4 device) can now work with a foreign socket (IPv6 resource)

**Examples**:

- An older printer (IPv4) communicates with a modern cloud system hosted on IPv6 infrastructure

![NAT46 Diagram](/ccna/Network-Fundamentals/images/NAT46-diagram.png)

---

## 🧠 Short Summary:

NAT64 = IPv6 client ↔ IPv4 server

NAT46 = IPv4 client ↔ IPv6 server

![NAT Diagram](/ccna/Network-Fundamentals/images/NAT-diagram.png)