# 🛠️ ansible-mac-update

> Automated macOS software + Homebrew update using Ansible — assisted by ChatGPT 😎

[![Ansible](https://img.shields.io/badge/Ansible-Playbook-00AAD4?logo=ansible)](https://docs.ansible.com/)
[![macOS](https://img.shields.io/badge/Platform-macOS-black?logo=apple)](https://apple.com/macos/)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

---

## 📋 What It Does

This playbook automates the following:

- ✅ Checks for available macOS software updates  
- 📥 Installs all pending macOS updates  
- 🍺 Runs `brew update` to refresh package metadata  
- ⬆️ Upgrades all installed Homebrew packages  
- 🧹 Cleans up outdated Homebrew files (`brew cleanup`)  
- 🗂️ Logs all actions into `~/update_log.txt`  

---

## 🚀 Usage

1. **Install Ansible** (if not yet):
> pip3 install --user ansible

📦 Requirements
* macOS with Command Line Tools installed
* Homebrew installed
* Python + pip
* Ansible (8.x or higher recommended)

📄 License
> This project is licensed under the MIT License — see the LICENSE file for details.

🙌 Credits
> Built with guidance from ChatGPT and powered by Ansible.
