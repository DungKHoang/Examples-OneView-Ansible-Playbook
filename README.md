# Examples-OneView-Ansible-Playbook
The repository contains a collection of Ansible playbooks for HPE OneView configuration

# Versions
   *  HPE OneView SDK Python v5.40  : https://github.com/HewlettPackard/oneview-python
   *  HPE OneView SDK Ansible v5.40 : https://github.com/HewlettPackard/oneview-ansible

# Ansible playbooks
   *  Sample-SPT.yml : iLO settings - network connections settings - BIOS settings
   *  Sample-SP.yml  : build server profile from template
   *  Sample-ethernetNetwork.yml : create Ethernet network
   *  Sample-logicalInterconnectGroup.yml : create 3-Frame LIG and 1-Frame LIG of Fibre Channel
   *  Sample-uplinkset.yml 
        - query interconnect type to get port name
        - query URI of network and network sets
        - create uplink set with uplink ports, nativeNterok and networks
