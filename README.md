# Control-802.1x
Ansible code to audit Cisco 802.1x port configuration.
- Connect to the device, generate the show running file and parse the content to the specific required information.
- Read the result and save it in a html format.

# Important
- Don't forget to fill the file group_vars/all with the username and password for ssh connection.
- Don't forget to fill the file inventory with the hostnames and ips
- Download the #ansible-network.network.engine# 
    command:  ansible-galaxy install -r roles/requirements.yml
