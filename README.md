# agear-starter-launch

Créateur de nouveau projet saytup et e-majine en une ligne de commande.

Installez **Agear Starter Launch** via npm :

```
npm install -g agear-starter-launch
```

## votre première fois ?

Une fois installé globalement sur votre ordinateur (étape précédente), **Agear Starter Launch** permet de créer un nouveau projet basé sur [Agear Starter](https://github.com/agear-digital/agear-starter).

Il lui suffit de connaître : 
- le nom de votre projet (il va créer le dossier)
- le repo du projet à récupérer (ce sera "agear-digital/agear-starter")

Voici la syntaxe :

```
agear-starter-launch nom-du-projet agear-digital/agear-starter
```

Ou si vous êtes déjà dans le dossier de votre projet :

```
agear-starter-launch . agear-digital/agear-starter
```


## pour aller plus vite encore

Si vous ne souhaitez pas préciser systématiquement le chemin vers le repo de Agear Starter, il est possible d'enregistrer votre configuration par défaut pour toutes les fois suivantes via `--configure`.

```
agear-starter-launch --configure
Set repository: agear-digital/agear-starter
Set key=value: (blank to skip) foo=bar
```

Puis il vous suffira de créer votre projet ainsi :

```
agear-starter-launch nom-du-projet
```

Ou encore mieux si vous êtes déjà dans le dossier de votre projet :

```
agear-starter-launch .
```

## License

MIT (auteur initial : Mathias Buus, cloné et adapté pour Agear Digital )