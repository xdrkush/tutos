# Commande submodule

Centralisation des tutos

Ajouter un nouveau submodule
`git submodule add [submodule-repository-url] [path]`
```sh
git submodule add https://... ./path
```

Initialiser les submodules du repo
```shell
git submodule init
```

Initialiser un submodule dans le repo
```shell
git submodule init [path]
```

Mettre à jour le repo
```shell
git submodule update
```

Récupérer les commits distants du repo:
```shell
git pull origin main
```

Récupérer les commits distants de tous les submodule:
```shell
git submodule foreach 'git pull origin main'
```

Ne pas oublier de push les modifications sur le repo centraliser
```shell
git push origin main
```

# Docs
  - Submodule: https://phoenixnap.com/kb/git-submodule
