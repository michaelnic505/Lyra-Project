# Lyra Project

**Lyra** is a modular client-server platform built entirely in **pure Java** with a **3-tier architecture** (Server, Shared, Client).  
All code is handcrafted and original, developed from scratch without external frameworks.

---

## **Project Overview**

Lyra is designed to demonstrate a clean and scalable Java architecture with the following layers:

1. **Server Layer (`lyra-service`)**
   - Handles socket-based communication with multiple clients.
   - Uses **Executor Services** for efficient multithreading.
   - Integrates **HikariCP** for high-performance database connection pooling.
   - Fully implemented and functional in this branch.

2. **Shared Layer (`lyra-shared`)**
   - Contains models and data structures shared between client and server.
   - **Pending implementation and currently empty**.

3. **Client Layer (`lyra-gui`)**
   - Handles user interface and client-side logic.
   - **Pending implementation and currently empty**.

---

## **Key Features**

- **Pure Java**: No frameworks, all code handcrafted.  
- **3-Tier Architecture**: Clear separation of server, client, and shared models.  
- **Socket Communication**: Real-time communication between clients and server.  
- **Concurrent Processing**: Executor Services for multiple client connections.  
- **High-Performance DB Access**: HikariCP integrated.  
- **Modular Design**: Separate branches for server, shared, and client modules.

---

## **Current Status**

- `server` branch: Fully implemented server infrastructure.  
- `shared` branch: Placeholder branch for shared models (not yet implemented).  
- `client` branch: Placeholder branch for client GUI and logic (not yet implemented).  

> The project is **actively under development**. Feedback and suggestions from the community are welcome to help shape the future implementation of `shared` and `client` modules.

---
## Project Structure (Planned)

Some pictures or images or whatever:

![Lyra Screenshot](https://github.com/michaelnic505/Lyra-Project/raw/server/Captura%20de%20pantalla%202025-11-28%20172701.png)


