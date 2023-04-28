# Ansible Playbooks

This repository contains a collection of Ansible playbooks for installing and configuring various software on Ubuntu servers. 
The playbooks are designed to make it easy for developers and system administrators to set up their servers without having to manually install and configure software.


The following playbooks are included:


- `install_Kubernetes.yml`: Installs and configures Kubernetes and Docker on Ubuntu servers.
- `install_MySQL.yml`: Installs MySQL server on Ubuntu servers.
- `install_apache.yml`: Installs and updates Apache web server on Ubuntu servers.
- `install_docker.yml`: Installs Docker on Ubuntu servers.
- `install_java11.yml`: Installs OpenJDK 11 on Ubuntu servers.
- `install_jenkins.yml`: Installs Jenkins on Ubuntu servers.
- `install_nginx.yml`: Installs and configures Nginx web server on Ubuntu servers.


## Requirements

- Ansible 2.9 or later installed on your local machine.
- SSH access to your target servers.
- Ubuntu 18.04 or later on your target servers.

## Usage

To use these playbooks, follow these steps:

1. Clone this repository to your local machine.
2. Modify the inventory file to include the IP addresses of your Ubuntu servers.
3. Run the appropriate playbook with the following command: 

ansible-playbook -i inventory <playbook-name>.yml

Replace `<playbook-name>` with the name of the playbook you want to run.
  

## Contributing

Contributions are welcome! If you find a bug or want to add a new playbook, please open an issue or pull request.

Feel free to fork and modify these playbooks to suit your needs.


