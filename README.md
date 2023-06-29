# pydog
<div style="text-align: center">
<img src="pydog.png" alt="Alt Text" width="300" height="300" class="center">
</div>

Pydog provides a minimal example of how to use Docker with Python in Visual Studio Code. Docker is a popular platform for creating, deploying, and running applications using containerization. Visual Studio Code is a powerful and widely used integrated development environment (IDE) that supports Docker integration.

## Prerequisites
Before getting started, ensure that you have the following prerequisites installed on your system:

### Windows
+ Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) on your system.
+ Install [Visual Studio Code](https://code.visualstudio.com/) on your system.
+ Install the following Visual Studio Code Extensions
  + Docker (ms-azuretools.vscode-docker)
  + Dev Container (ms-vscode-remote.remote-containers)

## Getting started
1. Clone this repository to your local machine using the following command:
```shell
git clone git@github.com:flojmn/pydog.git
```
2. Open Visual Studio Code and navigate to the "pydog" folder.
3. Press Ctrl + Shift + P to open the command palette, and select "pydog: Rebuild and Reopen in Container".
4. Start coding! Add additional packages to the [requirements.txt](requirements.txt) file.
5. To stop the pydog container, use the command "pydog: Stop Container" in the command palette.