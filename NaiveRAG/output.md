# Git Installation

# Windows

Enter the following commands on Command Prompt:

To install git
winget install id Git.Git -e source winget

Verify using git version

To install GitHub CLI
winget install id GitHub.cli -e source winget

Verify by running the command gh version

# Linux

Enter the following commands in the terminal:

To install git
sudo apt update
sudo apt install git

Verify by running the command git version

To install GitHub CLI
sudo apt install gh

Verify by running the command gh version

# MacOS

Run these commands in the terminal.

Download homebrew if not already installed by running the following:/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

When the above command is run, it will display three commands to be copied. Copy that and paste it in the terminal & run it to make sure that brew is added to the PATH of your system.

# Download git:

brew install git

# Download Github CLI

brew install gh

You can verify installations using git version & gh version.

Now Sign Up/Sign In to your GitHub account in a browser. Once signed in head back to the terminal and run the following command:

gh auth login

Now follow the on screen instructions.