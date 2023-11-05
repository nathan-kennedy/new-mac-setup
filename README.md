# Mac Development Environment Setup Script

Welcome to the Mac Development Environment Setup Script repository! This script is designed to automate the setup of a new Mac for development purposes. It's geared towards both experienced and novice developers looking to have a seamless setup experience.

## Features

- **Idempotent**: Run the script multiple times without causing unwanted side effects.
- **Error Handling**: Detects and logs errors to ensure a smooth setup process.
- **Automated Installation**: Automates the installation of essential tools, utilities, and applications to get you up and running quickly.
- **Customizable**: Easily add or remove applications to suit your needs.

## Getting Started

### Prerequisites

- Ensure you have administrative access to your Mac.
- Ensure you are logged into the App Store as some installations require it.

### Usage

1. Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/mac-dev-setup-script.git
cd mac-dev-setup-script
```

2. Make the script executable:
```bash
chmod +x setup.sh
```

3. Run the script:
```bash
./setup.sh
```

4. Follow the on-screen prompts. You might be asked to enter your password for certain installations.

## Customization

Feel free to customize the script to match your preferences. The script is structured and commented to make understanding and customizing straightforward. Add or remove applications in the arrays defined in the script to tailor the setup process to your needs.

## Error Logging

If there are any errors during the setup process, they will be logged and displayed at the end of the script execution. This allows for easy troubleshooting and manual installation if necessary.

## Contribution

Feel free to fork this repository and submit pull requests for any enhancements, bug fixes, or additional features you think would be beneficial. All contributions are welcome!

## Contact

For any questions or feedback, please feel free to reach out to Nathan Kennedy at nathankennedy1@gmail.com.
