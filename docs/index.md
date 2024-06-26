# Règle simple de documentation

NB: Vous êtes libre de faire évoluer l'ossature. Pensez juste à aviser les autres en cas de changement majeur.

## Principe de mise à jour

Ce repo contiendra 2 branches par defaut : main et develop. Pour apporter des modifications, vous pouvez:

- Créer une branche à partir de la branche develop. 
    - Exemple: 
        - feature/k8s/intro
        - feature/k8s/deployment

- Apporter vos modifications dans votre branche puis merger vers la branche develop.

Steps to get ready:

- cloner le repo
```
git clone https://github.com/wingufactory/lecloudfacile-k8s-training.git

git checkout -b develop

```

- Installer mkdocs: 

```
pip install mkdocs
```
- Executer le serveur de dev: 
```
cd lecloudfacile-k8s-training/
mkdocs serve
```


Cheers.