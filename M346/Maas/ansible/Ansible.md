# Commands

## Install ansible

    sudo apt update
    sudo apt install ansible

## See all hosts
    
    ansible-inventory --graph

## Ping a host

    ansible -m ping all

## Playbook

    ansible-playbook site.yml --check // Wird nichts verändert, nur ausprobiert
    ansible-playbook site.yml // wird verändert