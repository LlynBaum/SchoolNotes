# Maas

## Set Up

1. Download Wiregurd
2. Login in den [Maas Service](https://maas.bbw-it.ch/) von BBW
3. Create Wiregurd key
    - Create
    - Download Config File
    - Import in Wiregurd
4. Unter Help, gibt es ein Template für das yaml
5. `ssh-keygen` für den puplic key bekommen. Einfach Enter spamen
    - File Path öffnen
    - .pub file öffnen
    - Copy content
6. yaml file anpassen
    - Name zu einem belibigen Username
    - `ssh_authorized_keys` dein puplic key angeben
7. Maas VM erstellen
    - Lehrer angeben
    - yaml file content rein pasten
8. In cmd mit `ssh user@ip` verbinden