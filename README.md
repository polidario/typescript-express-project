# TypeScript Express Node Boilerplate for Shopify App Development

This boilerplate provides a solid foundation for developing Shopify apps using TypeScript, Express, and Node.js. It is designed to streamline the setup process and help you quickly get started with building robust and scalable Shopify applications.

## Features

- **TypeScript:** Enjoy the benefits of static typing and improved developer experience with TypeScript.
- **Express.js:** A fast, unopinionated, minimalist web framework for Node.js.
- **Shopify App SDK:** Easily integrate with Shopify by utilizing the official Shopify App SDK.
- **Authentication Middleware:** Includes a simple authentication middleware for securing your app's endpoints.
- **Environment Variables:** Utilize environment variables for configuration, ensuring a secure and flexible setup.
- **Linting and Formatting:** Integrated ESLint and Prettier configuration for consistent code style and quality.
- **Testing Setup:** Basic testing configuration using popular testing libraries for TypeScript projects.
- **Docker Support:** Docker configuration files for containerizing your app.

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js and npm: [Download Node.js](https://nodejs.org/)
- TypeScript: Install using npm (`npm install -g typescript`)
- ngrok: Required for local development and testing with Shopify apps. [Download ngrok](https://ngrok.com/download)

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/polidario/typescript-express-project.git
    cd typescript-express-project
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Create a `.env` file based on the provided `.env.example` and fill in your Shopify app credentials.**

4. **Start the development server:**

    ```bash
    npm run dev
    ```

5. **Use ngrok to expose your local server to the internet for testing:**

    ```bash
    ngrok http 3000
    ```

    Update your Shopify app settings with the ngrok URL (e.g., `https://random.ngrok.io`).

6. **Build and deploy your app when ready for production:**

    ```bash
    npm run build
    ```

## Directory Structure

- `src/`: Source code for your TypeScript application.
- `dist/`: Compiled TypeScript code.
- `public/`: Static assets (e.g., stylesheets, images).

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) when submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

Happy coding!
