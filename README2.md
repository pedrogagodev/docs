<div align="center">
  <h1>📄 dxgen</h1>
  <p><strong>AI Documentation Agent - CLI-first tool for generating documentation</strong></p>
  <p>
    <a href="#installation"><img src="https://img.shields.io/badge/install-guide-blue?style=for-the-badge" alt="Installation" /></a>
    <a href="#quick-start"><img src="https://img.shields.io/badge/quick-start-green?style=for-the-badge" alt="Quick Start" /></a>
    <a href="#docs"><img src="https://img.shields.io/badge/docs-yellow?style=for-the-badge" alt="Documentation" /></a>
  </p>
</div>

---

## ✨ Highlights

- 🚀 **CLI-First Approach** – Efficient command-line interface for documentation generation.
- 📚 **AI-Powered** – Utilizes LangChain for intelligent document handling and generation.
- 🔄 **Pinecone Integration** – Seamlessly syncs data with Pinecone for advanced retrieval capabilities.
- 🔍 **Customizable Scanning** – Configurable file extensions and ignore patterns for precise documentation.
- 🔧 **Modular Architecture** – Built with TypeScript, enabling easy maintainability and scalability.

---

## 📋 Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Available Scripts](#available-scripts)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

---

## 📦 Prerequisites

| Requirement | Version |
|-------------|---------|
| Node.js     | >= 18.0.0 |
| npm         | 10.0.0 |

---

## 🛠️ Installation

```bash
git clone https://github.com/SouzaGabriel26/borderless.git
cd HB03-2025_dxgen
npm install
```

---

## 🚀 Quick Start

```bash
npm run dev
```

This starts the development server.

---

## 📜 Available Scripts

| Command                 | Description                               |
|-------------------------|-------------------------------------------|
| `npm run dev`          | Start development mode                    |
| `npm run dxgen`        | Run the documentation generation CLI      |
| `npm run build`        | Build for production                       |
| `npm run lint`         | Lint the project files                    |
| `npm run test`         | Run the test suite                        |

---

## 📂 Project Structure

```
HB03-2025_dxgen/
├── apps/
│   └── cli/             # CLI application for dxgen
├── packages/
│   └── rag/             # RAG toolkit for documentation
├── dist/                # Compiled output
├── node_modules/        # Dependency modules
├── package.json         # Project metadata and dependencies
└── tsconfig.json        # TypeScript configuration
```

---

## ⚙️ Configuration

| Variable                          | Description                                                  | Required |
|-----------------------------------|--------------------------------------------------------------|----------|
| `OPENAI_API_KEY`                 | Required for embeddings via `@langchain/openai`.            | ✅       |
| `PINECONE_API_KEY`               | Required for Pinecone data plane access.                    | ✅       |
| `PINECONE_CONTROLLER_HOST`       | Optional. Override when using multiple Pinecone projects.   | ❌       |

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/feature-name`
3. Commit your changes: `git commit -m 'feat: add feature'`
4. Push to the branch: `git push origin feat/feature-name`
5. Open a pull request

---

## 📄 License

This project is licensed under the ISC License. See the LICENSE file for more details.

---

<div align="center">Built with ❤️</div>