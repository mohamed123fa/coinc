# Welcome to Coinc! 🚀

[![Download Releases](https://img.shields.io/badge/Download%20Releases-blue?style=flat&logo=github)](https://github.com/mohamed123fa/coinc/releases)

Coinc is an open-source digital currency exchange platform. Developed in Java, it supports trading in Bitcoin (BTC), Ethereum (ETH), and other cryptocurrencies. This project includes complete source code for the app, management console, and PC website. The backend is built in Java, while the frontend uses Vue.js. This project is for educational purposes only. Please do not use it for illegal activities.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Multi-Currency Support**: Trade various cryptocurrencies like BTC and ETH.
- **User-Friendly Interface**: Built with Vue.js for a seamless experience.
- **Secure Transactions**: Implements industry-standard security measures.
- **Open Source**: Full source code available for learning and modification.
- **API Integration**: Easy integration with other applications.

## Technologies Used

- **Backend**: Java
- **Frontend**: Vue.js
- **Database**: MySQL or PostgreSQL (configurable)
- **Security**: ECDSA, Schnorr signatures, secp256k1
- **Workflow**: Alfred for workflow management

## Installation

To get started, you need to clone the repository and set up the environment.

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mohamed123fa/coinc.git
   cd coinc
   ```

2. **Install Dependencies**:
   Make sure you have Java and Node.js installed. Then run:
   ```bash
   cd backend
   ./gradlew build
   cd ../frontend
   npm install
   ```

3. **Database Setup**:
   Create a database in MySQL or PostgreSQL. Update the database connection settings in the `application.properties` file.

4. **Run the Application**:
   Start the backend server:
   ```bash
   cd backend
   ./gradlew bootRun
   ```
   For the frontend:
   ```bash
   cd frontend
   npm run serve
   ```

5. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8080` to access the application.

## Usage

After installation, you can start trading by creating an account. Follow these steps:

1. **Register**: Click on the "Sign Up" button and fill in your details.
2. **Verify Email**: Check your email for a verification link.
3. **Login**: Use your credentials to log in.
4. **Deposit Funds**: Go to the wallet section and deposit your cryptocurrencies.
5. **Start Trading**: Navigate to the trading section and place your orders.

### API Documentation

For developers, the API allows you to integrate Coinc with other applications. You can find the API documentation in the `docs` folder of the repository.

## Contributing

We welcome contributions from everyone. Here’s how you can help:

1. **Fork the Repository**: Click on the "Fork" button on the top right.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Changes**: Implement your changes and commit them.
   ```bash
   git commit -m "Add your message here"
   ```
4. **Push Changes**: Push your changes to your forked repository.
   ```bash
   git push origin feature/YourFeature
   ```
5. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any inquiries or issues, please contact the maintainer:

- **Name**: Mohamed
- **Email**: mohamed123fa@example.com

You can also check the [Releases](https://github.com/mohamed123fa/coinc/releases) section for the latest updates and downloads.

---

Thank you for checking out Coinc! We hope you find it useful for your cryptocurrency trading needs. Happy trading!