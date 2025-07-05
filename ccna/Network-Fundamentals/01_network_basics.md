# 🌐 Network Basics & IP Addressing

A **computer network** is a group of interconnected computers or devices that share resources and information. These connections can be established through **wired (Ethernet)** or **wireless (Wi-Fi)** technologies.

> ✅ **Why use a network?**  
> Share files, printers, internet access, applications, and more efficiently across multiple systems.

---

## 🖥️ What Is a Server?

A **server** is a powerful computer that provides resources and services to other devices (clients) in the network. Each server typically includes:

- **CPU** (processing power)
- **RAM** (temporary memory)
- **Disk** (permanent storage)

---

## ☁️ Cloud & Data Centers

Servers are often stacked in **data centers** or **cloud platforms** (like AWS, Azure, or Google Cloud). These servers are:

- **Connected to the internet**
- **Accessible from anywhere** in the world
- **Highly scalable and redundant**

> 💡 **Example**:  
> When you send money online or stream a video, you're accessing data and services hosted on remote cloud servers over the internet.

---

## 🧭 How Devices Get IP Addresses

Each device on a network needs an **IP address** to communicate. There are **two IP versions** in use:

- IPv4 (e.g., `192.168.1.1`)
- IPv6 (e.g., `2001:0db8:85a3::8a2e:0370:7334`)

This assignment can happen in 3 ways:

---

## 1️⃣ Static IP Addressing

Manually assigning a fixed IP to a device.

**How it works**:
- Set directly on the device or router

**Use Cases**:
- Servers (web, DNS, mail)
- Printers
- NAS (Network Attached Storage)

**Pros**:
- IP never changes
- Good for port forwarding

**Cons**:
- Not scalable in large networks
- Potential for IP conflicts

---

## 2️⃣ Dynamic IP Addressing (via DHCP)

Assigned automatically by a **DHCP server**.

**How it works**:
- Router or server assigns IP from a pool

**Use Cases**:
- Homes, offices, guest networks

**Pros**:
- Easy to manage
- Avoids manual errors

**Cons**:
- IP can change unless a reservation is set

---

## 3️⃣ Automatic Private IP Addressing (APIPA)

Fallback method if no DHCP is available.

**How it works**:
- OS assigns an IP in the `169.254.x.x` range

**Use Cases**:
- Local-only networks
- Emergency fallback

**Pros**:
- Enables minimal local communication

**Cons**:
- No internet access
- Not suitable for production

---

## 🎯 Bonus: DHCP Reservation

Ensures a device always receives the **same IP** via DHCP based on its **MAC address**.

**Best for**:
- Printers
- Critical servers
- Devices that need consistent access

---

## 🌐 DNS – Domain Name System

Humans remember names like `google.com`, not IPs like `142.250.190.78`.

**DNS** resolves domain names to IP addresses and vice versa, just like a **phonebook** does for names and numbers.

> 📞 **Analogy**:  
> You know your friend as "Alice" (domain name), but your phone needs her number (IP) to call her.

---

## 🧠 Summary Diagram

The diagram below summarizes how devices get IP addresses, how DNS resolves domain names, and how everything ties together across networks and cloud infrastructure.

![Network Diagram](/ccna/Network-Fundamentals/images/network-diagram.png)
