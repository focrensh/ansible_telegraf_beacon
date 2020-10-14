# Ansible Telegraf Beacon

This example installs and configures various telegraf plugins to send data to F5 Beacon.

## Steps
* Update `vars.yaml` to include your Beacon Token, HTTP URLs, and DNS Domains to monitor.
* Update the inventory group **tgservers** in the `hosts` file to include your destination Ubuntu servers.
* `ansible-playbook push.yaml`