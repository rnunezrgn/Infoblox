# Infoblox playbooks example
Have your infoblox device named "nios" or a group named "nios", which contain a list of IPAM/DDI devices.
You can use a "machine" type credential in Ansible Controller with these playbooks.

1 - Make sure the Ansible Collection has been install.
    $ ansible-galaxy collection install infoblox.nios_modules
    
2 - Install the "infoblox-client" WAPI Package using pip or pip3:
    $ pip3 install infoblox-client
    
Infoblox NIOS modules on Ansible documentation
    
    - https://docs.ansible.com/ansible/latest/collections/infoblox/nios_modules/index.html
