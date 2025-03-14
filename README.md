![Autonomys Agents Banner_1](https://github.com/user-attachments/assets/340c2a09-ddc6-49c1-83af-ec9cdd30ac01)

# Autonomys Agents: A framework for building autonomous AI agents

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue)](https://www.typescriptlang.org/)
[![Autonomys Network](https://img.shields.io/badge/Autonomys-Network-green)](https://autonomys.network)

Autonomys Agents is an **EXPERIMENTAL** framework for building AI agents. Currently, the framework supports agents that can interact with social networks and maintain permanent memory through the Autonomys Network. We are still in the **EARLY STAGES OF DEVELOPMENT** and are actively seeking feedback and contributions.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Usage](#usage)
  - [Interactive CLI Interface](#interactive-cli-interface)
  - [Web CLI Interface](#interactive-web-cli-interface)
  - [Development Mode](#running-with-devall-web-cli-only)
- [Examples](#examples)
- [Character System](#character-system)
- [Context Size Management](#context-size-management)
- [Autonomys Network Integration](#autonomys-network-integration)
- [Resurrection System](#resurrection)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Features

- 🤖 Autonomous social media engagement
- 🧠 Permanent agent memory storage via Autonomys Network
- 🔄 Built-in orchestration system
- 🐦 Twitter integration (with more platforms planned)
- 🎭 Customizable agent personalities
- 🛠️ Extensible tool system
- 📊 Advanced context management
- 🔐 Secure memory encryption

## Installation

### Prerequisites

- Node.js (v16 or higher)
- Yarn package manager
- For Windows users: Visual Studio C++ Redistributable ([Download here](https://aka.ms/vs/17/release/vc_redist.x64.exe))

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/autonomys/autonomys-agents.git
   cd autonomys-agents
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```

## Quick Start

1. Create a new character:
   ```bash
   yarn create-character <your-character-name>
   ```

2. Configure your character:
   - Navigate to `characters/{your-character-name}/config`
   - Update `.env` with required environment variables
   - Modify `config.yaml` with your configuration
   - Customize `{your-character-name}.yaml` with personality settings

3. Run your agent:
   ```bash
   # Development mode with hot reload
   yarn dev <your-character-name>
   
   # Production mode
   yarn start <your-character-name>
   
   # Interactive CLI
   yarn cli <your-character-name>
   ```

## Usage

[Previous CLI Interface, Web CLI Interface, and dev:all sections remain unchanged]

## Examples

### Available Examples

- [Twitter Agent](examples/twitterAgent/README.md) - Demonstrates social media interaction
- [Multi Personality](examples/multiPersonality/README.md) - Shows how to create agents with multiple personalities

### Creating Your Own Agent

Refer to our [examples directory](examples/) for detailed implementation guides and best practices.

[Previous Character System, Context Size Management, and Autonomys Network Integration sections remain unchanged]

## Contributing

We welcome contributions to the Autonomys Agents framework! Here's how you can help:

### Ways to Contribute

1. **Report Bugs**
   - Use the GitHub issue tracker
   - Include detailed steps to reproduce
   - Provide system information

2. **Suggest Enhancements**
   - Open an issue with the enhancement tag
   - Describe the feature and its benefits
   - Provide examples if possible

3. **Submit Pull Requests**
   - Fork the repository
   - Create a feature branch
   - Follow the coding standards
   - Include tests and documentation
   - Submit a PR with a clear description

### Development Setup

1. Fork and clone the repository
2. Install dependencies: `yarn install`
3. Create a feature branch
4. Make your changes
5. Run tests: `yarn test`
6. Submit a pull request

### Code Standards

- Follow TypeScript best practices
- Include JSDoc comments
- Write unit tests for new features
- Update documentation as needed

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">Built with ❤️ by the Autonomys Network community</p>
