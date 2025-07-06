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