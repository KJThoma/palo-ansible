# palo-ansible
Example of how to configure Palo Alto firewalls using Ansible.

# Environment
* Ubuntu 18.04.5
* Ansible
* Ansible galaxy role paloaltonetworks.panos
* pip3 pan-os-python

# Directory Structure
```bash
.
├── ansible.cfg
├── inventory
│   ├── group_vars
│   │   └── palos
│   │       └── palo_spare.yml
│   └── hosts
└── playbooks
    ├── create-object.yml
    └── create-policy.yml

```

# References
* https://github.com/PaloAltoNetworks/pan-os-ansible
* https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-ubuntu
