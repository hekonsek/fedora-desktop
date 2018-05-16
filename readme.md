# Henry's Fedora desktop workstation

This is Ansible playbook I use to configure my Fedora 28 development workstation. I'm working on containerized Java and 
GoLang applications for cloud environment.

## Installation

To provision my Fedora workstation I install Ansible client, clone this project and run this playbook:

    sudo dnf install ansible
    git clone git@github.com:hekonsek/fedora-desktop.git
    cd fedora-desktop
    ansible-playbook fedora-desktop.yml --ask-sudo-pass