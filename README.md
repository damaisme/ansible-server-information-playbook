# Ansible Server Information Script

This Ansible script is designed to gather information about servers, including the number of cpus, memory, disk, OS, and IP address, and store the information in a CSV file.

## Requirements

* Ansible version 2.9 or higher
* Python 2 or 3

## Usage
Clone the repository to your local machine:
```
$ git clone https://github.com/amdadulbari/ansible-server-info.git
```
Edit the inventory file (inventory.ini) to specify the servers you want to gather information about.

Run the script:

```
ansible-playbook -i inventory.ini gather-server-info.yml
```
The script will connect to each server specified in the inventory file, gather the information, and store the information in a CSV file (report_DATE.csv) in the current working directory.

### Contributing
If you find any bugs or have suggestions for improvements, please feel free to submit an issue or a pull request.