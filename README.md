# OS X Ansible Playbook

Forked from [geerlingguy/mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook). You should probably look there.

## Installation

  1. [Install Ansible](http://docs.ansible.com/intro_installation.html).
  2. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  3. Clone this repository to your local drive.
  4. Run the command `$ ansible-galaxy install -r requirements.txt` inside this directory to install required Ansible roles.
  5. Run `ansible-playbook main.yml -i inventory --ask-sudo-pass` from the same directory as this README file.

