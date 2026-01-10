# Introduction to Cloud Computing and Traditional IT Infrastructure

How the internet works, server composition, and the limitations of traditional IT infrastructure, setting the stage for the necessity of **Cloud Computing**.

## 📚 Table of Contents
- [How Websites Work](#how-websites-work)
- [What is in a Server?](#what-is-in-a-server)
- [Basic Networking Terminology](#basic-networking-terminology)
- [Traditional IT vs. Real-World Problems](#traditional-it-vs-real-world-problems)

---

## How Websites Work

To access a website, a process occurs between the **Client** (user's browser) and the **Server** (machine hosting the website) via a **Network**.

### The Concept of IP Addresses
Both the Client and the Server need an **IP Address** to find each other.

> **Analogy (The Postal Service):**
> * **Data:** The letter.
> * **Client:** The sender.
> * **Server:** The recipient.
> * **Network:** The post office and delivery system.
> * **IP Address:** The address written on the envelope.

---

## What is in a Server?

A server is essentially a powerful computer composed of the following key components:

| Component | Function | Analogy (Human Body) |
| :--- | :--- | :--- |
| **CPU (Compute)** | Performs calculations and processing. | **The Brain** (thinking). |
| **RAM (Memory)** | Stores temporary information very quickly. | **Short-term memory**. |
| **Storage (Data)** | Stores data long-term (files). | Long-term memory. |
| **Database** | Stores data in a structured way for easy querying. | Structured notebooks/ledgers. |
| **Networking** | Devices like Routers, Switches, DNS. | Nervous system/communication. |

---

## Basic Networking Terminology

A network consists of cables, routers, and servers connected to each other.

1.  **Router:** A device that forwards data packets between different computer networks. It knows where to send your packets on the internet (like a delivery service).
2.  **Switch:** Once a packet arrives at the destination network, the Switch sends it to the correct specific device (client) within that network.

**Data Flow:** `Client` -> `Router` -> ...Internet... -> `Router` -> `Switch` -> `Destination Server`.

---

## Traditional IT vs. Real-World Problems

### The Evolution of Server Deployment
1.  **Early Stage:** Running servers at home or in a garage (e.g., Google in its early days).
2.  **Growth Stage:** Renting an office or a dedicated room as a **Data Center**.
3.  **Data Center Stage:** Buying more servers and racks to meet demand.

### The Pain Points
The traditional self-managed Data Center model faces significant obstacles:

* **Cost:** Rent, electricity, and cooling systems are expensive.
* **Maintenance:** Requires time and manpower to replace broken hardware and maintain the system.
* **Time:** Ordering, shipping, and installing new servers is time-consuming.
* **Scaling:** Limited. If demand suddenly increases 10x, you cannot scale up instantly.
* **Staffing:** Requires a team for 24/7 monitoring.
* **Disaster Risks:** Earthquakes, fires, or power outages can take down the entire system.

👉 **The Solution:** *Externalize* all these problems -> **Cloud Computing**.