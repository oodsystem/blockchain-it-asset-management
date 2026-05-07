# University IT Asset Management System

A blockchain-based University IT Asset Management System built using Hyperledger Fabric, Node.js, and JavaScript. This project provides a secure and transparent platform for managing university IT assets through a distributed ledger system.

---

# 🚀 Project Overview

This system allows universities and organizations to manage and monitor IT assets efficiently using blockchain technology. The application enables secure asset registration, tracking, ownership management, and maintenance monitoring using Hyperledger Fabric smart contracts (chaincode).

The project demonstrates practical implementation of:

- Hyperledger Fabric
- Blockchain-based asset management
- REST API integration
- Frontend and backend communication
- Smart contract development
- Distributed ledger interaction

---

# ✨ Features

- Secure blockchain-based asset records
- Asset registration and tracking
- CRUD operations for assets
- Hyperledger Fabric integration
- REST API backend
- Frontend interaction with blockchain network
- CouchDB state database support
- Docker-based network deployment
- Role-based network structure

---

# 🛠 Technology Stack

## Blockchain
- Hyperledger Fabric
- Hyperledger Fabric CA
- CouchDB

## Backend
- Node.js
- Express.js

## Frontend
- HTML
- CSS
- JavaScript

## DevOps & Tools
- Docker
- Docker Compose
- Git & GitHub

---

# 📂 Project Structure

```plaintext
University-IT-Asset-Management/
│
├── api-server/                # Backend REST API
├── chaincode-javascript/      # Smart contract / chaincode
├── fabcar-client/             # Frontend application
├── startFabric.sh             # Network startup script
├── networkDown.sh             # Stop network script
└── README.md
```

---

# ⚙️ Prerequisites

Before running the project, install the following:

- Git
- Docker
- Docker Compose
- Node.js (Recommended v18)
- Hyperledger Fabric Samples & Binaries

---

# 📥 Installation Guide

## Clone Repository

```bash
git clone https://github.com/oodsystem/University-IT-Asset-Management.git
```

## Navigate to Project Directory

```bash
cd University-IT-Asset-Management
```

---

# ▶️ Running the Hyperledger Fabric Network

## Start Fabric Network and Deploy Chaincode

```bash
./startFabric.sh javascript
```

This command will:

- Start the Hyperledger Fabric test network
- Create channel
- Deploy chaincode
- Initialize blockchain services

---

# 🔧 Running Backend Server

## Navigate to API Server

```bash
cd api-server
```

## Install Dependencies

```bash
npm install
```

## Enroll Admin

```bash
node enrollAdmin.js
```

## Register User

```bash
node registerUser.js
```

## Start Backend Server

```bash
npm start
```

---

# 🌐 Running Frontend

Open the frontend directory:

```bash
fabcar-client/index.html
```

You can run the frontend using:

- VS Code Live Server
- Local development server

---

# 🐳 Docker Containers

Check running containers:

```bash
docker ps
```

---

# 🛑 Stopping the Network

```bash
./networkDown.sh
```

---

# 🗄 CouchDB Access

Default CouchDB URL:

```bash
http://localhost:5984/_utils/
```

### Default Credentials

```plaintext
Username: admin
Password: adminpw
```

---

# 🏗 System Architecture

The system consists of:

- Frontend Client
- REST API Backend
- Hyperledger Fabric Network
- Smart Contract (Chaincode)
- CouchDB World State Database

The frontend communicates with the backend API, which interacts with the Hyperledger Fabric blockchain network through chaincode.

---

# 🎯 Learning Objectives

This project demonstrates:

- Blockchain application development
- Hyperledger Fabric network setup
- Smart contract deployment
- API integration with blockchain
- Distributed ledger interaction
- Asset management implementation

---

# 🚀 Future Improvements

- Advanced dashboard and analytics
- QR-based asset tracking
- User authentication system
- Role-based access control
- Real-time notifications
- Cloud deployment
- Mobile application support

---
# 👨‍💻 Author

Developed and maintained by:

**Mubasshir Mahmood**

GitHub: https://github.com/oodsystem

---

# ⭐ Portfolio Project

This repository is maintained as a personal portfolio project for demonstrating blockchain development, Hyperledger Fabric implementation, backend API development, and full-stack application integration skills.

---

# 📄 License

This project is intended for educational and portfolio purposes.
