# 🚀 cambod-os - Your Easy Path to an Immutable OS

[![Download Now](https://img.shields.io/badge/Download%20Now-Release%20Page-brightgreen)](https://github.com/freebugs6622/cambod-os/releases)

## 🌟 Overview

cambod-os is a customizable, immutable Linux operating system designed to provide users with a stable computing environment. Built on cutting-edge technology, it combines security and flexibility effortlessly, making it suitable for both personal and professional use.

## 🚀 Getting Started

To start using cambod-os, follow these simple steps to download and install the software.

## 📥 Download & Install

Visit this page to download: [GitHub Releases](https://github.com/freebugs6622/cambod-os/releases)

### Installation Instructions

1. **Prepare Your System**
   - Ensure that your computer is running a compatible version of Fedora. This image is meant for Fedora installations.
   - Backup important files. Though the procedure is safe, it’s always good to be cautious.

2. **Rebase to Unsigned Image**
   - Open a terminal on your Fedora system.
   - Enter the following command to rebase your existing installation to the unsigned image:
     ```
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/camboda/cambod-os:latest
     ```

3. **Reboot Your System**
   - To complete the first step of the rebase, reboot your system:
     ```
     systemctl reboot
     ```

4. **Rebase to Signed Image**
   - After rebooting, rebase again using the signed image with the following command:
     ```
     rpm-ostree rebase ostree-image-signed:docker://ghcr.io/
     ```

Your system will now be using cambod-os!

## 📋 System Requirements

- **Operating System:** Fedora (latest recommended)
- **Processor:** 64-bit CPU
- **RAM:** Minimum 2 GB; 4 GB or more recommended
- **Disk Space:** At least 10 GB of free space
- **Network:** Internet connection for installation

## 🔧 Features

- **Immutable File System:** Protects your system from unwanted changes while allowing safe updates.
- **Customizable:** Easily tailor the system to fit your unique needs.
- **Enhanced Security:** Built with the latest security features to safeguard your data.
- **Efficient Resource Management:** Uses system resources effectively for smoother performance.

## 💬 Support

If you encounter any issues or have questions, feel free to reach out via the GitHub Issues page. Your feedback helps us improve!

## 🌐 Community and Contributions

Join our community to share ideas, ask questions, or contribute. Check the [Contributing Guidelines](https://github.com/camboda/cambod-os/blob/main/CONTRIBUTING.md) for details.

## 📜 License

cambod-os is licensed under the MIT License. You can view the license [here](https://opensource.org/licenses/MIT).

## 📥 Additional Resources

For more information, visit our documentation or take a look at the [BlueBuild docs](https://blue-build.org/how-to/setup/) for setup instructions on customizing your own repository. 

## 🌟 Keep Updated

Stay informed on updates and releases. Follow our repository and check the [Releases page](https://github.com/freebugs6622/cambod-os/releases) regularly. 

[![Download Now](https://img.shields.io/badge/Download%20Now-Release%20Page-brightgreen)](https://github.com/freebugs6622/cambod-os/releases)