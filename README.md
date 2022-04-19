# FortiGate-Interop-Lab-Configurator-Ansible_Playbook

Ansible version of https://github.com/MoAl78741/FortiGate-Interop-Lab-Configurator


## Synopsis

The purpose of this app is to facilitate the setup of interoperability lab testing with various router/switch platforms in a specific environment. 

What the app does:

- Reads in config.yaml and passes to Jinja2 templating engine
- Converts specific YAML arguments into specified template code 
- Uses FortiManager API to backup the target FortiGate firewall
- Uploads the generated commands to the specified FortiManager ADOM as a CLI script