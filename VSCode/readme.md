# Visual Studio Code

## VS Code Tips & Tricks

[VS Code Tips & Tricks](https://github.com/Microsoft/vscode-tips-and-tricks)

[Useful VS Code Keyboard Shortcuts](https://zellwk.com/blog/useful-vscode-keyboard-shortcuts/)

## Setup

### Install Visual Studio Code on Windows

Download [VS Code](https://code.visualstudio.com/) and excute Setup

### Install Visual Studio Code on Raspi

```
wget https://packagecloud.io/headmelted/codebuilds/gpgkey -O - | sudo apt-key add -
curl -L https://raw.githubusercontent.com/headmelted/codebuilds/master/docs/installers/apt.sh | sudo bash
```

You can start VS Code from the Terminal using:

```
code-oss .
```

### Install .NET 5 on Raspi

Add the Microsoft package signing key to your list of trusted keys:

```
wget https://packages.microsoft.com/config/debian/10/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
```

Install the SDK:

```
sudo apt-get update;
sudo apt-get install -y apt-transport-https && \
sudo apt-get update && \
sudo apt-get install -y dotnet-sdk-5.0
```
