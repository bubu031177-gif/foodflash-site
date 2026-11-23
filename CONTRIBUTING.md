# Guide de contribution

Merci de contribuer à FoodFlash ! Ces règles permettent de garder le projet simple, cohérent et facile à maintenir.

## Conventions de commits

Utilisez le format [Conventional Commits](https://www.conventionalcommits.org/) :

```text
type: description courte à l'impératif
```

Types courants :

- `feat` : nouvelle fonctionnalité
- `fix` : correction de bug
- `docs` : documentation
- `style` : mise en forme sans changement de comportement
- `refactor` : réorganisation du code sans changement fonctionnel
- `test` : ajout ou modification de tests
- `chore` : maintenance ou tâches diverses

Exemples : `feat: ajouter une section de menu` ou `docs: préciser le lancement local`.

## Processus de pull request

1. Créez une branche dédiée à votre modification à partir de la branche principale.
2. Faites des changements ciblés et créez des commits selon les conventions ci-dessus.
3. Vérifiez le résultat dans un navigateur. Pour les changements visuels, contrôlez également l'affichage sur petit écran et sur ordinateur.
4. Ouvrez une pull request vers la branche principale. Décrivez le changement, sa motivation et les vérifications effectuées.
5. Ajoutez des captures d'écran pour les changements d'interface et répondez aux retours de revue avant la fusion.

## Standards de code

- Gardez la structure simple et utilisez HTML sémantique.
- Conservez `lang="fr"` dans le document et utilisez des libellés accessibles et explicites.
- Respectez le formatage existant : indentation de deux espaces et noms de classes CSS descriptifs.
- Placez les styles dans `style.css` et le JavaScript dans `app.js`; évitez les styles ou scripts intégrés au HTML.
- Limitez les dépendances externes et n'ajoutez-en pas sans nécessité.
- Mettez à jour la documentation lorsqu'un changement modifie l'utilisation ou le fonctionnement du projet.
- Avant d'envoyer une pull request, ouvrez `index.html` dans un navigateur et vérifiez l'absence d'erreurs dans la console.
