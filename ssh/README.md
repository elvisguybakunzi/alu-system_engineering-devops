# SSH Connection and RSA Key Pair Setup

## Table of Contents
- [General Information](#general-information)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [SSH Overview](#ssh-overview)
- [SSH RSA Key Pair Setup](#ssh-rsa-key-pair-setup)
- [Connecting to Remote Server](#connecting-to-remote-server)
- [Advantages of Using #!/usr/bin/env bash](#advantages-of-using--usrbinenv-bash)
- [Resources](#resources)
- [Contact](#contact)

## General Information
This project involves connecting to a remote Ubuntu server using SSH and setting up an SSH RSA key pair for secure authentication. You will find instructions and guidelines to complete the tasks efficiently.

## Learning Objectives
Upon completing this project, you should be able to explain the following topics without using external resources:
- What is a server and where servers usually live.
- Understanding SSH and its advantages.
- How to generate an SSH RSA key pair.
- How to connect to a remote host using an SSH RSA key pair.
- The benefits of using `#!/usr/bin/env bash` in scripts.

## Requirements
- Allowed editors: vi, vim, emacs
- The project will be interpreted on Ubuntu 20.04 LTS.
- All files must end with a new line.
- Include a README.md file at the root of the project folder.
- All Bash script files must be executable.
- The first line of each Bash script should be `#!/usr/bin/env bash`.
- Provide comments explaining the purpose of each script.

## SSH Overview
SSH (Secure Shell) is a cryptographic network protocol that allows secure communication and remote access between two computers. It provides encrypted data transmission, ensuring that sensitive information remains protected during transfer.

## SSH RSA Key Pair Setup
To set up an SSH RSA key pair, follow these steps:

1. Open a terminal on your local machine.
2. Use the `ssh-keygen` command to generate the key pair:
   ```bash
   ssh-keygen -t rsa -b 4096

   ```
