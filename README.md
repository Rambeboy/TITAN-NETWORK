# Titan Edge Installation Script

A simple installation script for setting up Titan Edge node with Docker.

## Overview

This script automates the installation process of Titan Edge node by:

- Checking and installing Docker if not present
- Pulling required Docker images
- Setting up the Titan Edge environment
- Binding the device with your hash

## Registration

Before installation, you need to register to get your hash:

1. Visit [Titan Edge Registration](https://test1.titannet.io/intiveRegister?code=zhNcuF)
2. Complete the registration process
3. After registration, obtain your hash:
   - Go to Console
   - Navigate to Node Management
   - Click on "Get Identity Code"
4. Save your hash for the installation process

## Requirements

- Linux-based operating system (Ubuntu/Debian or CentOS/RHEL/Fedora)
- Sudo privileges
- Internet connection
- Your Titan Edge hash (obtained from Node Management console)

## Supported Operating Systems

- Ubuntu
- Debian
- CentOS
- Red Hat
- Fedora

## Quick Start

1. Register and get your hash:

   - Register at [Titan Edge Registration](https://test1.titannet.io/intiveRegister?code=zhNcuF)
   - Go to Console > Node Management > Get Identity Code

2. Run this single command to download and execute the installation script:

```bash
curl -fsSL https://raw.githubusercontent.com/Galkurta/Titan-Network/main/install.sh -o install.sh && chmod +x install.sh && sudo ./install.sh
```

Or using wget:

```bash
wget https://raw.githubusercontent.com/Galkurta/Titan-Network/main/install.sh && chmod +x install.sh && sudo ./install.sh
```

The script will prompt you to enter your hash during installation.

## Features

- One-command installation
- Automatic Docker installation if not present
- Simple and minimalist interface
- Error handling and validation
- Automatic system detection
- Interactive hash input

## Troubleshooting

If you encounter any issues:

1. **Docker Installation Fails**

   - Ensure your system is up to date
   - Check your internet connection
   - Verify sudo privileges

2. **Container Fails to Start**

   - Ensure Docker service is running
   - Check if required ports are available
   - Verify system resources

3. **Binding Fails**
   - Verify your hash is correct (from Console > Node Management > Get Identity Code)
   - Check your internet connection
   - Ensure API endpoint is accessible

## Notes

- After Docker installation, you may need to log out and log back in for group changes to take effect
- The script requires internet access to download necessary components
- Make sure to keep your hash secure and do not share it with others
- If you haven't registered, make sure to do so before running the installation script
- Your hash can be found in the Node Management section of the console

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
