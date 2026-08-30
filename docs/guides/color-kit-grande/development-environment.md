# Development Environment

We will be working with a **PlatformIO** (PIO) development environment in **Visual Studio Code** (VS Code).
If you have never worked with PlatformIO, please install it as per their [installation instructions](https://docs.platformio.org/en/latest/integration/ide/vscode.html#installation).

## Installation Steps

0. [Download](https://code.visualstudio.com/) and install official Microsoft Visual Studio Code. PlatformIO IDE is built on top of it
1. Open VSCode Package Manager
2. Search for the official platformio ide extension
3. Install PlatformIO IDE.

![../../img/how-tos/platformio-install.png](../../img/how-tos/platformio-install.png)

### Install Git

The Weather Station project contains a library dependency that PlatformIO downloads from a Git repository. You therefore need a working Git client even if you downloaded the project itself as a ZIP file.

1. Download and install Git from [git-scm.com/install](https://git-scm.com/install/).
2. Completely restart Visual Studio Code after the installation.
3. Open a terminal and run `git --version` to verify that Git is available.

If PlatformIO displays `Please install git client from https://git-scm.com/download`, Git is either not installed or is not available on the system `PATH`.

Now please look at their [quick-start guide](https://docs.platformio.org/en/latest/integration/ide/vscode.html#quick-start):

[![](../../img/how-tos/platformio-quickstart.png)](https://docs.platformio.org/en/latest/integration/ide/vscode.html#quick-start)

## Video Tutorial

See the [Video Tutorials](video-tutorials.md) page for an instructional video on setting up the development environment.
