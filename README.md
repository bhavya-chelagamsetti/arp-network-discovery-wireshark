# 🛰️ Project: Discover Devices on Your Network using ARP

This project demonstrates how to discover all active devices in your local network using ARP requests and responses captured with Wireshark.

## 🔍 Objective
Capture ARP and broadcast traffic to identify the IP and MAC addresses of all devices on your network.

---

## 🖼️ Screenshots

| Screenshot | Description |
|-----------|-------------|
| ![start_capture_http.png](./start_capture_http.png) | ✅ **Start of Capture** — Wireshark begins capturing packets on the `Wi-Fi` interface. |
| ![arp_request.png](./arp_request.png) | 🟨 **ARP Request** — Device asks: "Who has `192.168.0.175`? Tell `192.168.0.183`". |
| ![arp_response.png](./arp_response.png) | 🟩 **ARP Response** — Reply: "`192.168.0.175` is at `2e:28:fc:28:6a:d3`". |


> ⚠️ *MAC and IP addresses shown are private/local and do not expose any personal or sensitive data.*

---

## 🧪 Test Setup
- **Tool**: Wireshark
- **Interface**: Wi-Fi
- **Filter Used**: `arp or broadcast`
- **Network**: Home Wi-Fi with multiple devices connected

---

## 🧠 What You Learn
- Understand ARP discovery process
- See which devices are actively communicating
- Analyze MAC addresses and their vendor identifiers
- Identify which device made each request or response

---

## 📌 Educational Purpose Only
This demonstration is meant for personal learning and awareness. It does **not involve scanning external networks** or violating privacy.


