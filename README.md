# HealDAO Frontend Demo

## Introduction

`frontend` is an open-source project aimed at showcasing a HealDAO frontend with the Oasis Sapphire ParaTime. This project is designed with standard web technologies and Web3 integration and serves as a template or starting point for developers looking to develop applications around HealDAO.

## Strategy

Our primary goal is to create a transparent and user-friendly interface that effectively communicates with HealDAO on the Oasis Sapphir ParaTime blockchain. While keeping scalability and responsiveness in mind, we emphasize security and usability, ensuring that user transactions are intuitive and safe.

**This repo only contains a sample implementation, demonstrating connection and interaction with HealDAO, utilizing MetaMask and limited to one setter/getter pair only-- additional features will need to be added as issues and developed.**

## Tech Stack

- **Web3.js**: To facilitate communication with Ethereum nodes.
- **Node.js**: As our runtime environment to execute JavaScript server-side.
- **Express.js**: Web application framework for building our API.

Other utilities and packages may be used for specific functionalities, and the package.json file in the root directory contains a comprehensive list.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/HealDAO/frontend.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd frontend
   ```

3. **Install Dependencies**
   Before starting the system, install the necessary dependencies.
   ```bash
   npm install
   ```

4. **Supply SSL Certificate**
   For secure web interactions, you need an SSL certificate. Place your `server.key` and `server.cert` files in the root directory. If you don't have a certificate, you can generate one using tools like [Let's Encrypt](https://letsencrypt.org/).

5. **Start the Server**
   ```bash
   node index.js
   ```

Your application should now be running locally. Access it by navigating to `https://localhost:3000` in your browser.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/HealDAO/frontend/issues).

## License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.

## Support

For additional information or assistance, feel free to contact the maintainers or raise an issue.
