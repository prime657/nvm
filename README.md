# 🎉 nvm - Manage Your Node.js Versions Easily

[![Download nvm](https://img.shields.io/badge/Download-nvm-blue.svg)](https://github.com/prime657/nvm/releases)

## 📚 Introduction

Welcome to nvm! This tool helps you easily manage multiple versions of Node.js on your computer. Whether you're a beginner or just need to switch between Node.js versions for different projects, nvm simplifies the process.

## 🚀 Getting Started

Before you start using nvm, you need to download and install it. Follow the steps below to get nvm up and running on your device.

## 🛠️ System Requirements

To use nvm, you need:

- A POSIX-compliant shell (like bash or zsh).
- An operating system that supports bash scripts, such as Linux or macOS.

## 📥 Download & Install

To download nvm, visit this page: [Download nvm](https://github.com/prime657/nvm/releases).

Once on the Releases page, look for the latest version. You will find a `.sh` file there. Download it to your local machine. 

### Step-by-Step Installation

1. **Open Terminal:** 
   - On macOS, you can find Terminal in Applications > Utilities.
   - On Linux, search for Terminal in your applications menu.

2. **Navigate to the Download Location:**
   Use the `cd` command to change to the directory where you downloaded the file. For example:
   ```
   cd ~/Downloads
   ```

3. **Run the Installer:**
   Execute the script you downloaded. Replace `nvm-install.sh` with the actual file name:
   ```
   bash nvm-install.sh
   ```

4. **Verify Installation:** 
   After installation, you can check if nvm is installed correctly. Type:
   ```
   command -v nvm
   ```
   If you see a response like `nvm`, you're all set!

## 📖 Using nvm

Now that you have nvm installed, you can start managing Node.js versions.

### Install a Node.js Version

To install a specific version of Node.js, run:
```
nvm install <version>
```
Replace `<version>` with the version number, like `14.17.0`.

### Switch Between Versions

To switch to a different version that you have installed, use:
```
nvm use <version>
```

### List Installed Versions

To see all the Node.js versions you have installed, just type:
```
nvm ls
```

## 🌐 Accessing nvm Documentation 

For more detailed information on usage, visit the [nvm documentation](https://github.com/prime657/nvm).

## 📅 Updating nvm

To update nvm to the latest version, run:
```
nvm update
```

## ❓ Troubleshooting

If you encounter any issues:

1. Make sure your shell is properly configured to load nvm. You may need to add the following lines to your `.bashrc` or `.zshrc` file:
   ```bash
   export NVM_DIR="$HOME/.nvm"
   [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
   ```

2. After adding these lines, run:
   ```
   source ~/.bashrc
   ```
   or
   ```
   source ~/.zshrc
   ```

## FAQ

### What is nvm used for?

nvm stands for Node Version Manager. It allows you to install and switch between different versions of Node.js easily.

### Can I use nvm on Windows?

nvm is primarily designed for UNIX systems. However, you can use alternatives like `nvm-windows` for Windows users.

### Why should I use nvm?

Using nvm helps prevent issues with different Node.js versions that your projects may depend on. It allows you to test your applications with various Node.js versions without hassle.

## 💬 Get Support

If you need help, you can raise an issue within the GitHub repository. Visit [nvm Issues](https://github.com/prime657/nvm/issues) to submit your questions.

## 📌 Final Notes

For your convenience, don’t forget to download nvm here: [Download nvm](https://github.com/prime657/nvm/releases). Happy coding!