*HASN'T BEEN TESTED YET - FEEL FREE TO TEST YOURSELF - WILL BE RUNNING THIS SCRIPT IN THE NEXT COUPLE DAYS ON AN OLDER MAC AND AGAIN IN A VIRTUAL MACHINE ON AN M1 - I'LL UPDATE THIS README WHEN FINISHED*

# Mac Development Environment Setup Script

Welcome to the Mac Development Environment Setup Script repository! This script is designed to automate the setup of a new Mac for development purposes. It's geared towards both experienced and novice developers looking to have a seamless setup experience. It installs all of my personal picks for the best packages, tools, and software when working on a Mac.

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

# Installed Software List

This document provides an overview of the software and tools that the setup script installs, categorized to give you a clear understanding of each component's purpose and utility.

## Development Tools

- **Xcode Command Line Tools**: Essential tools for macOS development, including compilers and command-line utilities.
- **Homebrew**: The "missing package manager" for macOS, used to install and manage software.
- **Zsh**: Z shell, a Unix shell that can be used as an interactive login shell and as a command interpreter for shell scripting.
- **Cask**: Extension for Homebrew for installing macOS native applications.
- **Raycast**: A productivity tool allowing you to control your tools with a few keystrokes.
- **mas**: Mac App Store command-line interface that simplifies the installation of App Store applications.

## Terminals and Shells

- **iTerm2**: A replacement for Terminal and the successor to iTerm that brings powerful features for command-line users.
- **neovim**: A hyperextensible Vim-based text editor.

## Text Editors and IDEs

- **Visual Studio Code**: A lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux.

## Command-Line Utilities

- **archey4**: A system information tool designed for macOS.
- **asciinema**: Terminal session recorder that lets you record and share your command-line workflows.
- **bat**: A clone of `cat` with syntax highlighting and Git integration.
- **colordiff**: A wrapper for `diff` and produces the same output but with colored syntax.
- **diff-so-fancy**: Improves the display of diff outputs.
- **duf**: A better alternative for checking disk usage.
- **exa**: A modern replacement for 'ls' with color and Git integration.
- **fd**: A simple, fast and user-friendly alternative to 'find'.
- **fzf**: A general-purpose command-line fuzzy finder.
- **glances**: A cross-platform system monitoring tool written in Python.
- **htop**: An interactive process viewer for Unix systems.
- **inxi**: A powerful command-line system information script for console and IRC.
- **rar**: A command-line tool for creating and viewing RAR archives.
- **speedtest-cli**: Command line interface for testing internet bandwidth using speedtest.net.
- **pandoc**: A universal document converter.
- **tealdeer**: A very fast implementation of `tldr` in Rust: Simplified and community-driven man pages.
- **tree**: A recursive directory listing command that produces a depth-indented listing of files.
- **wifi-password**: Shows the current WiFi network password.
- **z**: Tracks the most used directories to allow quick navigation.

## Programming Languages

- **node.js**: A JavaScript runtime for server-side programming.
- **python**: A versatile scripting language used for a wide range of applications.

## Productivity Tools

- **Hidden Bar**: An ultra-light MacOS utility that helps hide menu bar icons.
- **DropOver**: A utility that makes dragging and dropping files or content easier.
- **aldente**: A charging limiter for MacBooks to help extend the battery's lifespan.
- **alt-tab**: A window switcher for macOS that allows switching between windows in a more convenient way.
- **logseq**: A privacy-first, open-source knowledge base that works on top of local plain-text Markdown and Org-mode files.

## Browsers

- **brave browser**: A free and open-source web browser based on the Chromium web browser and its Blink engine focused on privacy.

## Utility Apps

- **cheatsheet**: An app that shows keyboard shortcuts in an overlay window.
- **clean my Mac x**: A cleaning and optimization tool for Mac.
- **utm**: A virtual machines manager for Mac, designed to create virtual machines that can run on Apple Silicon.
