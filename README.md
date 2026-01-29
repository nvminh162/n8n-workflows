# 🔄 n8n Workflows

<div align="center">

![n8n](https://img.shields.io/badge/n8n-Workflows-EA4B71?style=for-the-badge&logo=n8n)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![Automation](https://img.shields.io/badge/Automation-Ready-success?style=for-the-badge)

**J4f: Discover n8n technology**

A collection of powerful automation workflows built with [n8n](https://n8n.io/) - the fair-code licensed workflow automation platform.

[Features](#-features) • [Getting Started](#-getting-started) • [Workflows](#-workflows) • [Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Getting Started](#-getting-started)
- [Workflows](#-workflows)
- [Installation](#-installation)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 🎯 About

This repository contains a curated collection of n8n workflows designed to automate various tasks and processes. Whether you're looking to streamline your business operations, integrate multiple services, or automate repetitive tasks, these workflows provide ready-to-use solutions.

**n8n** is a powerful workflow automation tool that allows you to connect various services and automate tasks with a visual workflow editor. It's extendable, fair-code licensed, and can be self-hosted.

## ✨ Features

- 🚀 **Ready-to-Use**: Import and deploy workflows instantly
- 🔧 **Customizable**: Easily modify workflows to fit your needs
- 📦 **Well-Organized**: Structured workflow collection
- 🔐 **Self-Hosted**: Complete control over your automation
- 🎨 **Visual Workflows**: Easy to understand and maintain
- 🔄 **Integration-Ready**: Connect with 400+ apps and services

## 📦 Prerequisites

Before you begin, ensure you have the following installed:

- [n8n](https://docs.n8n.io/hosting/) (self-hosted or cloud)
- Node.js (v14.15 or higher)
- npm or yarn package manager

## 🚀 Getting Started

### Installing n8n

You can install n8n in multiple ways:

#### Using npx (Recommended for testing)
```bash
npx n8n
```

#### Using npm globally
```bash
npm install n8n -g
n8n
```

#### Using Docker
```bash
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
```

#### Using Docker Compose
```bash
docker-compose up -d
```

After installation, n8n will be available at `http://localhost:5678`

## 📁 Workflows

This repository contains the following workflows:

### Available Workflows

Coming soon! Workflows will be organized in the `/workflows` directory.

<!-- Example structure:
- **Workflow Name 1** - Brief description
  - File: `workflows/workflow-name-1.json`
  - Purpose: What it does
  - Integrations: Services used

- **Workflow Name 2** - Brief description
  - File: `workflows/workflow-name-2.json`
  - Purpose: What it does
  - Integrations: Services used
-->

## 💾 Installation

### Clone the Repository

```bash
git clone https://github.com/nvminh162/n8n-workflows.git
cd n8n-workflows
```

### Import Workflows

1. Open your n8n instance at `http://localhost:5678`
2. Navigate to **Workflows** → **Import from File**
3. Select the workflow JSON file from the `/workflows` directory
4. Configure credentials for the services used in the workflow
5. Activate the workflow

## 🎮 Usage

### Importing a Workflow

1. **Download the workflow file** from the `/workflows` directory
2. **Open n8n** in your browser
3. Click on **"Workflows"** → **"Import from File"**
4. Select the downloaded JSON file
5. **Configure credentials** for any nodes that require authentication
6. **Test the workflow** using the "Execute Workflow" button
7. **Activate the workflow** when ready

### Customizing Workflows

- Click on any node to modify its configuration
- Add or remove nodes using the "+ Add node" button
- Connect nodes by dragging from output to input
- Use the Expression Editor for dynamic data manipulation
- Test individual nodes using the "Execute Node" feature

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-workflow
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing workflow for task automation'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-workflow
   ```
5. **Open a Pull Request**

### Workflow Submission Guidelines

When submitting a new workflow:

- ✅ Include a clear description of what it does
- ✅ Document all required credentials and configurations
- ✅ Test the workflow thoroughly
- ✅ Export as JSON with clear naming
- ✅ Add documentation in the PR description

## 📖 Resources

- [n8n Documentation](https://docs.n8n.io/)
- [n8n Community Forum](https://community.n8n.io/)
- [n8n Workflow Templates](https://n8n.io/workflows)
- [n8n YouTube Channel](https://www.youtube.com/c/n8n-io)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 Nguyen Van Minh
```

## 👤 Contact

**Nguyen Van Minh** - [@nvminh162](https://github.com/nvminh162)

Project Link: [https://github.com/nvminh162/n8n-workflows](https://github.com/nvminh162/n8n-workflows)

---

<div align="center">

**If you find this repository helpful, please consider giving it a ⭐ star!**

Made with ❤️ and n8n

</div>