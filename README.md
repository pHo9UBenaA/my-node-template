# my-node-template

This repository is a template for Node.js projects, integrating Biome and TypeScript for a streamlined development experience.

## Features

- **Node.js**: JavaScript runtime built on Chrome's V8 engine.
- **Biome**: Tool for code formatting, linting, and more.
- **TypeScript**: Typed superset of JavaScript that compiles to plain JavaScript.
- **PNPM**: Fast, disk space-efficient package manager.
- **Docker**: Containerization platform to package applications.

## Getting Started

Follow these steps to set up and run the project:

### Prerequisites

- [Node.js](https://nodejs.org/) installed.
- [PNPM](https://pnpm.io/) installed globally.
- [Docker](https://www.docker.com/) installed (if using Docker).

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/pHo9UBenaA/my-node-template.git
   cd my-node-template
   ```

2. **Install dependencies**:

   ```bash
   pnpm install
   ```

### Using Docker

To run the application inside a Docker container:

1. **Build the Docker image**:

   ```bash
   docker-compose build
   ```

2. **Start the container**:

   ```bash
   docker-compose up -d
   ```

3. **Access the container**:

   ```bash
   docker-compose exec node bash
   ```

## Development

- **Linting and Formatting**:

  Biome is configured for linting and formatting. To check for issues:

  ```bash
  pnpm biome check
  ```

  To fix issues:

  ```bash
  pnpm biome write
  ```

- **TypeScript Compilation**:

  To compile TypeScript files:

  ```bash
  pnpm tsc
  ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 
