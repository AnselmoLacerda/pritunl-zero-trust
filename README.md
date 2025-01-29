Sure! Here's a draft for your README documentation:

---

# Pritunl Zero Trust

Welcome to the Pritunl Zero Trust repository! This project aims to provide a comprehensive solution for implementing zero trust security with Pritunl.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Pritunl Zero Trust is designed to enhance your security posture by implementing zero trust principles. It includes configurations and scripts to ensure a secure and efficient deployment.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Docker installed on your machine
- Basic knowledge of shell scripting

## Installation

To install Pritunl Zero Trust, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/AnselmoLacerda/pritunl-zero-trust.git
    cd pritunl-zero-trust
    ```

2. Run the installation script:
    ```sh
    ./init.sh
    ```

## Usage

After installation, you can start using Pritunl Zero Trust by following these steps:

1. Build the Docker image:
    ```sh
    docker-compose up -d
    ```

2. Retrieve the default password:
    ```sh
    ./get_default_pass.sh
    ```

3. Access the Pritunl web interface and log in with the retrieved password.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Create a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template to better fit your project's needs! If you need any more help, just let me know.
