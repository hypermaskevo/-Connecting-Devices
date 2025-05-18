# -Connecting-Devices
This lab demonstrates how to properly connect various networking devices in Cisco Packet Tracer using appropriate cabling. It simulates both short and long-distance connections with proper cable types based on real-world practices. The focus is on building physical topology with routers, switches, and end devices.
![image](https://github.com/user-attachments/assets/66b36fd4-1730-4a9d-b88b-f768cb16cc2e)


# 🔗 Cisco Packet Tracer Lab – Day 02: Connecting Devices

## 📘 Overview

This lab demonstrates how to properly connect various networking devices in Cisco Packet Tracer using appropriate cabling. It simulates both short and long-distance connections with proper cable types based on real-world practices. The focus is on building physical topology with routers, switches, and end devices.

## 🧱 Topology Components

- 🖥️ **PCs (x3)** – Connected to access switches
- 🖧 **Cisco Switches (x8)** – Multiple layers of access and distribution
- 🌐 **Cisco Routers (R1–R4)** – Interconnecting the networks
- 💽 **Server (x1)** – Connected to SW8

## 🌐 Distances & Connections

| Connection | Interface | Distance | Cable Type |
|------------|-----------|----------|-------------|
| R1 – R2    | Fa0/0 – Fa0/0 | 50 meters  | Copper Straight-Through |
| R1 – R3    | Gig2/0 – Gig3/0 | 3 kilometers | Fiber |
| R3 – R4    | Gig3/0 – Gig3/0 | 250 meters | Fiber |
| Access Switches to PCs / Server | Fa0/x | ~5–20 meters | Copper Straight-Through |

> ⚠️ **Note:** Auto-MDIX is disabled. Be mindful of crossover vs straight-through cables where applicable.

## 🔌 Objectives

- Practice correct cabling between routers, switches, and PCs
- Understand copper vs fiber usage based on distance
- Learn interface labeling and physical topology best practices

## 🛠️ Instructions

1. Use the labels in the diagram to determine connections.
2. Select proper cable types manually (do **not** use “Automatically Choose Connection”).
3. Consider the physical distances when selecting fiber or copper.
4. Verify all link lights turn green.

## ✅ Tasks Completed

- [x] Devices placed
- [x] Labeled links
- [x] All physical connections established manually
- [ ] IP configuration (optional for next lab)

## 📂 File

- `Day02-Lab.pkt` – Packet Tracer file with device connections (rename accordingly)

---

**Author:** Yurii Vysotskyi
**Date:** May 2025  
