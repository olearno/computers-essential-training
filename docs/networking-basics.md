# Networking Basics

Understanding basic networking concepts helps you connect your computer to the internet and other devices. In this section, you’ll learn how to find your IP address, understand gateways, and know the difference between static and dynamic IPs.

---

## What You Will Learn

- What an IP address is
- How to find your IP address and gateway
- The difference between static and dynamic IP addresses
- Basic network troubleshooting commands

---

## Try It Yourself

Spend up to one hour exploring these networking basics on your computer.

---

### 1. Find Your IP Address

- **Windows:**  
  - Open Command Prompt and run: `ipconfig`
- **Mac/Linux:**  
  - Open Terminal and run: `ifconfig` or `ip a`

Write down your IPv4 address.

---

### 2. Find Your Gateway

- **Windows:**  
  - In the `ipconfig` output, look for "Default Gateway".
- **Mac/Linux:**  
  - In the `ifconfig` or `ip a` output, or run: `ip route` and look for "default via".

Write down your gateway address.

---

### 3. Static vs Dynamic IP

- **Static IP:** An address that does not change and is set manually.
- **Dynamic IP:** An address assigned automatically by a DHCP server and may change over time.

**Exercise:**  
- Check if your computer is set to use a static or dynamic IP.
  - Windows: Go to Network & Internet settings > Adapter options > Right-click your connection > Properties > Internet Protocol Version 4 (TCP/IPv4) > Properties.
  - Mac: System Preferences > Network > Select your connection > Advanced > TCP/IP.
  - Linux: Check your network manager or look for `dhcp` in your config files.

---

### 4. Test Your Network Connection

- **Ping a website:**
  - Windows/Mac/Linux: `ping google.com`
- **Check open network connections:**
  - Windows: `netstat -an`
  - Mac/Linux: `netstat -an` or `ss -tuln`

---

### 5. Bonus: Find Your Computer Name

- **Windows:** `hostname`
- **Mac/Linux:** `hostname`

---

## Reflection

- What is your IP address and gateway?
- Is your IP static or dynamic?
- Did you have any trouble connecting to the internet?
- Write a short summary of what you learned about networking.