# Ping 📡

**Ping** is a high-concurrency, distributed real-time messaging engine built to explore the challenges of building scalable communication systems. 

## 🏗 High-Level Architecture
Ping is designed with **Scalability** and **Reliability** as core pillars.

- **Backend:** Developed in **Go (Golang)** to leverage its efficient concurrency model (goroutines) and high-performance networking capabilities.
- **Real-time Protocol:** Uses **WebSockets** for persistent, low-latency, bi-directional communication.
- **Distributed State:** Utilizes **Redis Pub/Sub** to enable seamless message routing across multiple server instances.
- **Persistence:** **PostgreSQL** ensures data integrity and supports message history for users returning from a disconnected state.

## 🚀 Key Features (V1 Roadmap)
- [ ] **Stateful Connections:** Maintaining persistent WebSocket connections with efficient resource management.
- [ ] **Horizontal Scaling:** Distributed message delivery via Redis, allowing the system to scale beyond a single node.
- [ ] **Fault Tolerance:** Robust handling of "dirty" disconnects and message sequencing to ensure zero data loss.
- [ ] **Secure Auth:** JWT-based authentication with hashed password storage.

## 🛠 Tech Stack
- **Language:** Go 1.2x+
- **Database:** PostgreSQL
- **Cache/Broker:** Redis
- **Containerization:** Docker (Planned)