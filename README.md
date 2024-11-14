# Ansible Network Automation for Cisco Devices
**A Beginner's Guide to Network Automation with Ansible and Cisco**

---

**🚧 Project Status: In Progress 🚧**

> **Note:** This project is currently under active development. The full project structure, playbooks, and other files are being worked on and will be added soon. Please check back for updates!

---

## Overview
This project is designed as a practical guide to help network engineers, especially beginners, dive into network automation using Ansible for Cisco devices. ...



# ansible-cisco-network-automation
A beginner’s guide to automating Cisco network device configurations with Ansible, featuring step-by-step playbook setups, device inventory creation, and practical examples to streamline workflows and reduce configuration errors for network engineers

Ansible Network Automation for Cisco Devices
A Beginner's Guide to Network Automation with Ansible and Cisco
Overview
This project is designed as a practical guide to help network engineers, especially beginners, dive into network automation using Ansible for Cisco devices. With network complexity increasing and automation becoming essential, this project demonstrates a step-by-step approach to setting up Ansible, configuring network devices, and automating repetitive tasks.

By the end of this guide, you’ll understand how to leverage Ansible to streamline configuration workflows, save time, and reduce error, all while advancing your skills as a network automation specialist.

Motivation
With over a decade of experience in computer networking, I've observed that the role of network engineers is rapidly evolving. Today’s network engineer must balance traditional networking skills with automation and programming expertise to keep up with industry demands and technological advances. This project is aimed at bridging that gap by providing hands-on experience with Ansible, enabling network engineers to enhance their efficiency, accuracy, and value in the field.

Prerequisites
To follow along with this project, you will need:

Cisco Devices: Cisco switch (3550) and Cisco router (4200 series) running IOS version 16.9.5 or later.
Linux System: A Linux machine for Ansible installation and management.
Ansible and Python: Familiarity with Python is beneficial. You will need Ansible installed on your Linux machine along with necessary Python libraries.

Key Features:
Setting Up Ansible on Linux: Learn how to install and configure Ansible, including managing dependencies such as the paramiko library for SSH connections.

Creating an Inventory File: Define target devices using Ansible's inventory file (.ini), specifying connection details and allowing agentless orchestration.

Building Your First Playbook: Understand the structure and purpose of playbooks, written in YAML, to automate configuration tasks on Cisco devices.

Hands-on Network Configuration Automation: Create templates for tasks like configuring interface descriptions and enabling interfaces, all from your playbook.

Project Structure
inventory/: Contains the .ini file defining network devices and their access parameters.
playbooks/: Contains Ansible playbooks written in YAML to automate specific configuration tasks.
scripts/: Additional scripts or Python helper files used in conjunction with Ansible (e.g., scripts for additional device-specific configurations).

Usage
Clone the repository: Start by cloning this repository.

git clone https://github.com/yourusername/ansible-network-automation-cisco.git
cd ansible-network-automation-cisco
Set Up Inventory File: Open the provided .ini file in the inventory/ directory to specify your Cisco device IP addresses and access credentials.
Run the Playbook: Execute your playbook with the following command:

ansible-playbook -i inventory/agents.ini playbooks/configure_devices.yml
Review Results: Ansible will provide a summary after the playbook execution, showing successful and failed tasks.

Conclusion:
This project aims to provide a foundation in network automation using Ansible and Cisco devices. It’s perfect for network engineers looking to expand into automation, combining both the CLI skills of traditional networking with powerful automation techniques.

For a detailed walkthrough and video tutorial, check out my YouTube channel where I share additional insights and upcoming projects.
https://www.youtube.com/watch?v=MU4rl0Nv890

Note: Contributions and suggestions are welcome! If you have ideas for expanding this project or would like to collaborate on future automation projects, please feel free to reach out.
