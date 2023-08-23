# Webstack Debugging Project #0

## Introduction

Welcome to the Webstack Debugging Project! This project is designed to help you practice debugging webstacks, an essential skill for Full-Stack Software Engineers. In this series, you'll be given broken or bugged webstacks and your task is to identify the issues and fix them to bring the webstack to a working state.

## Project Overview

In this example, we are given a simple scenario where a server must have two elements to function properly:

1. A copy of the `/etc/passwd` file in the `/tmp` directory.
2. A file named `/tmp/isworking` containing the string "OK".

Without these two elements, the web application cannot work as expected.

## Fixing the Webstack

To manually fix the webstack, follow these steps:

1. **Copy /etc/passwd to /tmp:**
   Use the following command to copy the `/etc/passwd` file to the `/tmp` directory:

   ```bash
   sudo cp /etc/passwd /tmp/
