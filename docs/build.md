# Build

## Building Rivendell From Source
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
