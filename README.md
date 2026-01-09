# Workflows

Code your workflow. Automate your world.

Workflows is an open-source platform designed for developers who want to build and manage automation without the limitations of "no-code" tools. It provides a professional editor environment where you can write, schedule, and monitor JavaScript processes for everything from simple daily tasks to complex enterprise data integrations.

## Why Workflows?

Most automation tools force you into rigid boxes. Workflows takes a different approach by putting the code first. If you can write JavaScript, you can automate anything. 

By using Workflows, you get a dedicated space to:
* **Write logic in JavaScript:** Use the language you already know to handle complex conditional logic and data transformation.
* **Schedule with precision:** Built-in support for CRON jobs means your scripts run exactly when they need to.
* **Integrate anywhere:** Connect to any API, database, or service that supports HTTP requests or NPM packages.
* **Manage everything in one place:** A clean, centralized dashboard to see what is running, what failed, and what's next.

## Core Features

* **First-Class Editor:** A full-featured web editor designed for writing clean, readable automation scripts.
* **Automated Scheduling:** Native CRON support for recurring tasks.
* **Data Integration:** Tools built specifically to help move data between different systems and platforms.
* **Environment Management:** Securely manage your API keys and secrets.
* **Open Source:** Self-host the entire platform to keep your data and logic private.

## Getting Started

### Prerequisites

You will need a few things installed on your machine to get started:
* Node.js (version 18 or higher)
* A package manager like npm, yarn, or pnpm
* A PostgreSQL database instance

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/flexcodelabs/workflows-ui.git
   cd workflows
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure your environment**
   Create a `.env` file in the root directory. You can use `.env.example` as a starting point.
   ```bash
   cp .env.example .env
   ```

4. **Initialize the database**
   ```bash
   npx prisma migrate dev
   ```

5. **Start the application**
   ```bash
   npm run dev
   ```

Once the server is running, visit `http://localhost:3000` to create your account and start building.

## Contributing

Workflows is built by and for the community. We welcome all kinds of contributions, whether you are fixing a small typo in the documentation or proposing a major new feature. 

To contribute:
1. Fork this repository.
2. Create a branch for your feature or fix.
3. Submit a pull request with a clear description of your changes.

We strive to maintain a welcoming and helpful environment for everyone.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as you see fit.

## Support

If you run into issues or have questions, please open an issue on GitHub or join our community discussions. We are always happy to help.