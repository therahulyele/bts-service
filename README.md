# Beyond The Streets (BTS) - Microservices Repository

Welcome to the **Beyond The Streets (BTS)** microservices repository! This project powers a mobile application for **real-time bus tracking**. The repository uses a **monorepo structure** and implements a microservices architecture using **Go** and **Node.js**.

---

## 🛠️ Features

- **Real-Time Tracking**: Track buses live with high precision.
- **Scalable Microservices**: Modular and decoupled services for ease of development and deployment.
- **Multi-Language Support**: Services written in Go and Node.js.

---

## 📁 Repository Structure

```
bts-microservices/
├── services/
│   ├── bus-tracking/        # Service for real-time bus tracking
│   ├── user-management/     # Service for user authentication and profiles
│   ├── notifications/       # Service for notifications and alerts
│   └── ...                  # Additional services
├── shared/
│   └── libs/                # Shared libraries and utilities
├── docs/                    # Documentation for APIs and architecture
└── README.md                # This file
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v16 or higher)
- **Go** (v1.20 or higher)
- **Docker** (optional but recommended)
- **PostgreSQL** / **MongoDB** (depending on service requirements)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/therahulyele/bts-service.git
   cd bts-service
   ```

2. Install dependencies for Node.js services:
   ```bash
   cd services/<service-name>
   npm install
   ```

3. Build Go services:
   ```bash
   cd services/<go-service-name>
   go build
   ```

---

## 🛠️ Running Services

### Using Docker (Recommended)
1. Build and start all services:
   ```bash
   docker-compose up --build
   ```

2. Access services via their exposed ports (defined in `docker-compose.yml`).

### Without Docker
Run each service manually:
- For Node.js services:
  ```bash
  npm start
  ```
- For Go services:
  ```bash
  ./<service-name>
  ```

---

## 📚 Documentation

Find API documentation and architecture details in the `docs/` directory:
- **API Specs**: Detailed specifications for each service.
- **System Design**: Overview of architecture and workflows.

---

## 📞 Support

For questions or issues, please open an issue in this repository or contact [contact@therahulyele.com](mailto:contact@therahulyele.com).

---

## 💡 Contribution

We welcome contributions! Please check out the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to get involved.

---

## 🛡️ License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 🌐 Connect with Me

- **Instagram**: [@therahulyele](https://instagram.com/therahulyele)
- **X**: [@therahulyele](https://x.com/therahulyele)
- **LinkedIn**: [@therahulyele](https://linkedin.com/in/therahulyele)

---

Happy coding! 🚀