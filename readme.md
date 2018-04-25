# Henry's Fedora desktop workstation

This is Ansible playbook I use to configur my Fedora 27 development workstation. I'm working on containerized Java and 
GoLang applications for cloud environment.

## Installation

    dnf install ansible
    git clone git@github.com:hekonsek/fedora-desktop.git
    cd fedora-desktop
    ansible-playbook fedora-desktop.yml --ask-sudo-pass