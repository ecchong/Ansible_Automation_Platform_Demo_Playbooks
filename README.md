# Ansible_Automation_Platform_Demo_Playbooks

* **ping.yml** - simple ping playbook

* **collections/requirements.yml** - demonstrate using of `requirements.yml` to install collections

* **controller_configs/** - sample for Controller configuration
  ````shell
  ansible-playbook redhat_cop.controller_configuration.configure_controller.yml -e controller_configs_dir=$PWD/controller_configs
  ````
