# Gmail Creator Stealth Bot 🤖

![Gmail Creator Stealth Bot](https://img.shields.io/badge/Gmail%20Creator%20Stealth%20Bot-v1.0.0-blue)

Welcome to the **Gmail Creator Stealth Bot** repository! This project offers an automated solution for creating Gmail accounts with stealth-grade features. The bot utilizes anti-detect browser profiles and orchestrates workflows using n8n, ensuring that your account creation remains under the radar.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Workflow Overview](#workflow-overview)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Automated Account Creation**: Create Gmail accounts without manual intervention.
- **Anti-Detect Browser Profiles**: Utilize profiles that minimize detection risks.
- **n8n Workflow Orchestration**: Integrate complex workflows seamlessly.
- **Fingerprint Spoofing**: Change browser fingerprints to avoid detection.
- **Proxy Rotation**: Use multiple proxies for enhanced anonymity.
- **Human-Like Behavior**: Simulate natural user interactions.
- **Incognito Mode**: Operate in a secure environment.
- **Multi-Login Support**: Manage multiple accounts effortlessly.

## Installation

To get started with the Gmail Creator Stealth Bot, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/juanbastor/Gmail-Creator-Stealth-Bot.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd Gmail-Creator-Stealth-Bot
   ```

3. **Install Dependencies**:
   Use npm or yarn to install the required packages:
   ```bash
   npm install
   ```

4. **Download the Latest Release**:
   Visit the [Releases](https://github.com/juanbastor/Gmail-Creator-Stealth-Bot/releases) section to download the latest release. Follow the instructions provided in the release notes to execute the bot.

## Usage

To run the bot, execute the following command in your terminal:

```bash
node index.js
```

### Configuration

Before running the bot, you may need to configure some settings. Open the `config.json` file and adjust the parameters according to your needs. Here are some key configurations:

- **proxy**: Set your proxy server details.
- **browserProfile**: Choose your preferred anti-detect profile.
- **gmailAccountDetails**: Fill in the necessary account details for creation.

### Example Configuration

```json
{
  "proxy": "http://your-proxy:port",
  "browserProfile": "stealth-profile",
  "gmailAccountDetails": {
    "firstName": "John",
    "lastName": "Doe",
    "username": "john.doe",
    "password": "your-password"
  }
}
```

## Workflow Overview

The Gmail Creator Stealth Bot operates through a series of orchestrated workflows. Here's a simplified overview:

1. **Initialize Browser**: The bot launches an anti-detect browser.
2. **Set Proxy**: It connects through a proxy to mask your IP.
3. **Create Account**: The bot fills in the necessary details and submits the form.
4. **Verification**: It handles any verification steps required by Gmail.
5. **Store Credentials**: Finally, it saves the created account details for future access.

## Technologies Used

- **Node.js**: The backend framework for executing the bot.
- **Playwright**: For browser automation and interaction.
- **n8n**: For workflow orchestration.
- **Proxy Services**: To ensure anonymity during account creation.
- **Fingerprint Spoofing Libraries**: To modify browser fingerprints.

## Contributing

We welcome contributions to improve the Gmail Creator Stealth Bot. If you want to contribute, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button on the top right corner of the repository page.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**:
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to Your Branch**:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request."

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, feel free to reach out:

- **Juan Bastor**: [juanbastor@example.com](mailto:juanbastor@example.com)
- **GitHub**: [juanbastor](https://github.com/juanbastor)

---

Explore the power of automation with the Gmail Creator Stealth Bot. For the latest updates, visit the [Releases](https://github.com/juanbastor/Gmail-Creator-Stealth-Bot/releases) section.