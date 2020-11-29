# home-assistant-ansible
Mes roles ansibles pour creer mes entities et mes dashboards

# Launch
Pour tout build :
```
ansible-playbook --ask-become-pass ha.yml
```
Pour build seulement les entités ou le tableau de bord:
```
ansible-playbook --ask-become-pass --tags entities ha.yml
ansible-playbook --ask-become-pass --tags lovelace ha.yml
```
