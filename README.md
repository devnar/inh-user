# inh-user Repository Setup Guide

The "inh-user" repository is essential for integrating with the "I'm Not Hacker Terminal" platform, allowing users to set up and manage their terminal profiles. Follow these steps to create your `inh-user` repository and link it with "I'm Not Hacker Terminal."

## 1. Create a Repository Named `inh-user` on GitHub

On GitHub, create a new repository named `inh-user`. This repository will store scripts that you can run within the terminal, setting up your custom terminal profile on the platform.

## 2. Create Required Files

### a. JavaScript File
- To start using the terminal, create a uniquely named `.js` file in this repository. This file will be used to log in to the platform and will be paired with your browser fingerprint.
- Example file name: `123456789.js`. This file name should match your fingerprint ID.

### b. `dm.csv` File
- To send and receive direct messages, create a `dm.csv` file. Each line in this file should represent a message between users.
- Format each line as `sender, message`.
  - Example:
    ```csv
    username,Hey there
    username,Are you online
    ```

## 3. Copy the GitHub Raw Link

After creating your files, copy the **raw** link for each file. For example, the raw link for `123456789.js` should look like this: https://raw.githubusercontent.com/{your_username}/inh-user/main/{your_userid}.js
This link will be stored in LocalStorage with the key `userRawUrl` and will be loaded automatically during your terminal session.

## 4. Keep Your Files Updated

If you make any changes to your terminal scripts or messages, update the files in your `inh-user` repository to ensure the latest content is available in your terminal.

---

This guide helps users configure the `inh-user` repository correctly, enabling smooth integration with the "I'm Not Hacker Terminal."
