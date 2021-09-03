# Playbook ansible pour déployer Wordpress

## Utilisation

### Préparer l'inventaire

    cp inventory{.dist,}

Changer les variables pour correspondre à vos IP, login, password etc.

### Lancer le Playbook

    ansible-playbook -i inventory playbook.yml

By Julien T.
