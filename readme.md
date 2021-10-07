# Projet Le Blog de Batman

## installation

### Cloner le projet

```
git clone https://github.com/rhanmikael/leblogdebatman.git
```

### modifier les paramètre d'environnement dans le fichier .env (changer user_db et password_db)

### déplacer le terminal dans le dossier cloné

```
cd leblogdebatman
```

### taper les commandes suivantes :

```
composer install
symfony console doctrine:database:create
symfony console make:migration
symfony console doctrine:migrations:migrate
```