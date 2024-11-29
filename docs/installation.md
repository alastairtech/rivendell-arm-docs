# Installation

### Building Rivendell Debian Packages From Source
The buildlatest.sh script is an automated build system that generates Debian packages. It does not install or setup Rivendell. When running the script it will install all the required packages and ask you which version of Rivendell you wish to build. It will also install the Debian Multimedia Repository to be able to use the latest audio codec packages during the build.

```bash
# Make sure curl is installed
sudo apt install curl
```
```bash
# Download the build script
curl -o buildlatest.sh https://raw.githubusercontent.com/alastairtech/rivendell-arm/refs/heads/main/buildlatest.sh
```
```
# Make the build script executable
chmod +x buildlatest.sh
```
```
# Run the build script to generate Rivendell Debian 
sudo ./buildlatest.sh
```
### Installing From Local Packages
TBC

### Install Script
A fresh Rivendell 4 install script is avalibale for Debian 12 Bullseye systems. Download and install the lastest [Raspberry Pi OS](https://www.raspberrypi.com/software/) or [Armbian](https://www.armbian.com/download/?device_support=Standard%20support) and follow the commands below.

```bash
# Make sure curl is installed
sudo apt install curl
```
```bash
# Download the install script
curl -o install.sh https://raw.githubusercontent.com/alastairtech/rivendell-arm/refs/heads/main/install.sh
```
```
# Make the install script executable
chmod +x install.sh
```
```
# Run the script to install Rivendell
sudo ./install.sh
```
