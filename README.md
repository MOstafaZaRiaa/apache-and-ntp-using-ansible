# Apache and NTP Using Ansible

This repository contains an Ansible playbook for automating the setup of a LAMP (Linux, Apache, NTP) stack on CentOS servers.

## Introduction

This repository provides Ansible playbooks that automate the configuration of Apache web server and NTP time synchronization on your systems. This Ansible playbook streamlines the installation and configuration process, enabling you to quickly set up an environment on CentOS servers.

## Features

- Automated installation of Apache, and NTP on CentOS servers.
- Configuration of Apache to serve web content.
- Easy customization of playbook variables to adapt to specific requirements.
- Repeatable and standardized deployment process for consistent results.

## Requirements

- CentOS server(s) with SSH access.
- Ansible installed on the control machine.

## Usage

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/MOstafaZaRiaa/apache-and-ntp-using-ansible
2. Modify the inventories/hosts file to include the IP addresses or hostnames of your CentOS servers. Open the file and add the IP addresses or hostnames under the [centos_servers] group.
3. Adjust any desired variables in the apache folder. Open the folder and modify variables such as package versions, Apache configurations, settings, etc., according to your requirements.
4. Run the Ansible playbook:
   ansible-playbook -i inventory.ini playbook.yml
   This will execute the playbook and set up the specifications on CentOS servers.
5. After completion, you can access the web server by navigating to [http://"server-ip"] in your web browser.
# Customization
You can customize the playbook by modifying the following files:

- inventories: Add or remove server IP addresses or hostnames to control which servers the playbook runs on.
- apache folder: Adjust variables, package versions, or configuration options to suit your requirements.
# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.   
 
