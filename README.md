# 🚀 SecuScan – CI/CD & Static Analysis for Frontend Applications

**SecuScan**
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
git submodule init
git submodule update --recursive --remote
docker compose up -d
```

---

## 📦 Tech Stack

| Layer      | Technology                        |
| ---------- | --------------------------------- |
| Frontend   | React                             |
| Backend    | Python (REST API)                 |
| Analyzer   | Java CLI Tool                     |
| Deployment | SSH / FTP / Docker / Custom       |

---
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
