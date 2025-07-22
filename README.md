# 🚀 SecuScan – CI/CD & Static Analysis for Frontend Applications

**SecuScan**
---

## 🧩 Key Features

* **Static Code Analysis**: Catch bugs, enforce coding standards, and get actionable insights using our Java-powered analysis engine.
* **Remote Deployment**: Push builds directly to your configured server(s).
* **Multi-language Stack**:

  * **Frontend**: React
  * **Backend API**: Python (FastAPI)
  * **Static Analysis Engine**: Java CLI tool

---

## 📦 Tech Stack

| Layer      | Technology                        |
| ---------- | --------------------------------- |
| Frontend   | React                             |
| Backend    | Python (REST API)                 |
| Analyzer   | Java CLI Tool                     |
| Deployment | SSH / FTP / Docker / Custom       |

---

## 🚀 Getting Started

### Prerequisites

* Git
* Docker

---

### 🛠️ Installation

Clone the repo:

```bash
git clone https://github.com/your-org/secuscan.git
cd secuscan
git submodule update --recursive --remote
docker compose up -d
```

---

## ⚙️ Configuration

Update your deployment targets in:

```bash
config/deploy.config.json
```

Example:

```json
{
  "host": "your.remote.server",
  "user": "deploy",
  "path": "/var/www/your-app",
  "method": "ssh"
}
```

---

## 🧪 Static Analysis

The analyzer scans for:

* Code smells
* Unused imports
* Duplicate code
* CSS-in-JS issues
* Linting violations
---

## 👨‍💻 Development

* Dev frontend: `npm start`
* Dev backend: `uvicorn main:app --reload`
* Watch analyzer: use IDE build tools or `./gradlew build --continuous`
