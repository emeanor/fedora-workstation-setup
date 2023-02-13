# Fedora Workstation Setup
This is a basic Ansible playbook I created to automate the setup of my Fedora 37 development workstation. It is pretty light on installed packages, on the assumption that most dependencies will be installed inside Docker containers. In a nutshell, it:

- Removes unwanted applications that come installed on the system.
- Updates the system.
- Installs necessary system packages.
- Installs common applications like Chromium, VLC Media Player, etc.
- Installs development tools like Docker, VS Code, and Postman.
- Performs a minimal Git configuration.
- Tweaks the GNOME desktop GUI.

Automating these tasks has saved me a lot of time already, and I plan to keep expanding this playbook as time goes on.
