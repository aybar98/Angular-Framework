# Angular - Json Server web application

il s'agit d'une application Web simple qui utilise Angular et Json Server pour créer une application Web simple pouvant être utilisée pour créer, lire, mettre à jour et supprimer des données d'un fichier json.

## Installation

vous devez clonner le repo et executer les commandes suivantes :
```bash
npm install
```
assurez-vous que json-server est installé globalement, sinon exécutez la commande suivante :
```bash
npm install -g json-server
```

## Utilisation

1- assurez-vous d'avoir le fichier data/db.json dans le répertoire racine du projet, sinon créez-en un et ajoutez les données nécessaires.
2- pour exécuter l'application, exécutez d'abord le json-server en utilisant la commande suivante :
```bash
json-server --watch data/db.json --port 8080
```
3- puis lancez l'application angulaire à l'aide de la commande suivante :
```bash
ng serve
```
4- ouvrez votre navigateur et allez sur http://localhost:4200/ pour voir l'application en cours d'exécution.

## Captures d'écrans :

la première capture d'écran montre la page de connexion, où l'utilisateur peut se connecter en utilisant son nom d'utilisateur et son mot de passe.

![1](https://github.com/Yahyaa55/JEE_Activity_five/assets/100850367/52cc6058-1923-41a3-a22d-f3cb06eb5aba)

la deuxième capture d'écran montre la page d'accueil, où l'utilisateur peut voir la barre de navigation et le bouton de déconnexion à côté de son nom d'utilisateur.

![2](https://github.com/Yahyaa55/JEE_Activity_five/assets/100850367/18e4ce18-5c8f-4381-be24-3b89893fe9c9)

la troisième capture d'écran montre la page des produits, où l'utilisateur peut voir la liste des produits et rechercher un produit spécifique à l'aide de la barre de recherche.

![3](https://github.com/Yahyaa55/JEE_Activity_five/assets/100850367/b9b9e920-1d0e-40ff-b2f8-32d64ecd3601)

la quatrième capture d'écran montre la page d'ajout de produit, où l'utilisateur ne peut pas ajouter de produit à moins qu'il ne soit un administrateur.

![4](https://github.com/Yahyaa55/JEE_Activity_five/assets/100850367/dd001f9a-10d7-418e-8dbb-397abc74f3c2)

la dernière capture d'écran montre que pour un utilisateur administrateur, le composant d'ajout de produit est disponible et il peut ajouter un produit à la liste des produits.

![5](https://github.com/Yahyaa55/JEE_Activity_five/assets/100850367/ca2f932c-17c6-490f-a755-f62857c72017)
