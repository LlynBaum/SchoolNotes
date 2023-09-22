# Multipass

Command and other things about Multipass

## Commands

| Befehlt | Beschreibung |   
| :------ | :---------- |
| `multipass list` | lists all instances |  
| `multipass launch` | Creates and Starts new Ubuntu instance |  
| `multipass shell <name>` | open shell for the VM | 

### multipass launch

| Parameter | Beschreibung |   
| :------ | :---------- |
| `-n` | Name der Intance |  
| `--cloud-init` | Filepath zum init file |

#### Example
`multipass launch -n ref01 --cloud-init .\cloud-init-ref01.yml`

## Repo

`git clone https://gitlab.com/bbwrl/m346-ref-card-01.git`

`cd m346-ref-card-01`