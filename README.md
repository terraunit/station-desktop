# Station Desktop

Station Desktop is a desktop cryptocurrency wallet for the Terra blockchain. It provides a dedicated application environment for accessing and managing a wallet on Windows, macOS, and Linux.

## About Station Desktop

Station Desktop provides a dedicated desktop interface for accessing a wallet on the Terra blockchain. The application is intended to provide a convenient, standalone interface for working with a cryptocurrency wallet without relying solely on a browser window.

This repository contains the desktop application source code, tools for local development, and scripts for producing distributable application builds.

## Getting Started

### Prerequisites

To run or build Station Desktop from source, you will need:

- [Node.js](https://nodejs.org/en/) (LTS version recommended)
- npm (included with Node.js)
- Git, to clone the repository

### Install Dependencies

In the project directory, install dependencies:

```bash
npm install
```

### Development

Start the application in development mode:

```bash
npm run start
```

## Building the Application

Build scripts are provided for Windows, macOS, and Linux. Production build artifacts are written to the `dist` directory.

### Windows and macOS

```bash
npm run build-macwin
```

### Linux

```bash
npm run build-linux
```

Build requirements and generated package formats may vary by operating system and development environment.

## Security

Protect your wallet credentials and recovery information. Never share your recovery phrase or private keys, and carefully verify recipient addresses and transaction details before approving a transfer.

## Source Code and Releases

Source code, project updates, and TerraUnit releases are available on [GitHub](https://github.com/terraunit/station-desktop).

## License

Station Desktop is licensed under the MIT License. See the [LICENSE](LICENSE) file for the full license text.
