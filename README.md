# Ansible Workstation
Playbooks to setup developer workstations and laptops.


### Installation

  1. Ensure Apple's command line tools are installed.
  2. Install Ansible.
  3. Clone this repository to your local drive.
  4. Run `ansible-playbook main.yml --ask-sudo-pass` to run all playbooks

## Running Select Playbooks

To only run select tagged playbooks, use the following command. The `--tags` flag allows you to run any number of tagged playbooks by name.

    ansible-playbook main.yml -i inventory -K --tags "homebrew,github"
