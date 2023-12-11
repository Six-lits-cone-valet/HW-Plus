# Bienvenue dans notre guide de contribution ! 🎉

Nous sommes ravis que vous envisagiez de contribuer à notre projet. Votre aide est essentielle pour le maintenir et le développer.

## Comment contribuer ?

### Étape 1 : Forker le dépôt

La première étape pour contribuer à ce projet est de le "forker". C'est un moyen de créer votre propre copie du projet sur laquelle vous pouvez travailler.

1. Sur la page du dépôt, cliquez sur le bouton 'Fork' en haut à droite. Cela créera une copie du dépôt dans votre compte GitHub.
2. Clonez le dépôt forké sur votre machine locale en utilisant `git clone`. Remplacez `your-username` par votre nom d'utilisateur GitHub et `repo-name` par le nom du dépôt.

    ```bash
        git clone https://github.com/your-username/repo-name.git
    ```

### Étape 2 : Installer l'extension dans Chrome

Après avoir forké et cloné le dépôt, vous pouvez installer l'extension dans Chrome.

1. Ouvrez Chrome et allez à `chrome://extensions`.
2. Activez le mode développeur en haut à droite.
3. Cliquez sur 'Charger l'extension non empaquetée' et sélectionnez le dossier de l'extension dans votre système de fichiers local.

Et voilà ! Vous avez maintenant installé l'extension dans Chrome.

### Étape 3 : Faire des modifications et les soumettre

Une fois que vous avez fait vos modifications, vous pouvez les "commit" et les "push" sur GitHub.

1. Créez une nouvelle branche pour vos modifications. Remplacez `branch-name` par le nom que vous voulez donner à votre branche.

    ```bash
        git checkout -b branch-name
    ```

2. Committez vos modifications avec un message descriptif.

    ```bash
    git commit -m "Description of changes"
    ```

3. Poussez vos modifications sur GitHub.

    ```bash
    git push origin branch-name
    ```

4. Allez sur la page de votre fork sur GitHub, et cliquez sur 'New Pull Request' pour soumettre vos modifications à l'examen.