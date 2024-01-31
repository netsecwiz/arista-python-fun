Automated Ansible Setup for Client and Data Center Configuration
This project includes a set of Python scripts designed to automate the creation of Ansible configuration files. These scripts facilitate the generation of hosts, variables, and playbook files that are tailored for different clients and data center needs.

Prerequisites
Ensure Python is installed on your system and that you have the necessary permissions to execute Python scripts.

Instructions
Step 1: Generate the Hosts File
Run the hosts-builder.py script to create the Ansible hosts file:

bash
Copy code
python3 hosts-builder.py
This script will prompt you for the necessary details and output a configured hosts file for use with Ansible.

Step 2: Generate the Variable File
Execute the var-builder10.py to construct the variable file required for Ansible:

bash
Copy code
python3 var-builder10.py
Follow the interactive prompts provided by the script to input your specific configuration parameters.

Step 3: Create Ansible Playbooks
Utilize the playbooks-builder.py to automatically generate playbooks for the specified environments:

bash
Copy code
python3 playbooks-builder.py
The script will guide you through the creation process and produce ready-to-use Ansible playbooks.

Note: These scripts are interactive and will guide you through the necessary steps to input your configuration data. If you encounter any permissions issues, you may need to add executable permissions to the scripts with the command chmod +x *.py.
