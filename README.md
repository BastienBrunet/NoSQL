# NoSQL : Top de jeux play Store

## Notre Dataset
Voici le lien de notre dataset qui a été validé par notre manager : 
https://www.kaggle.com/datasets/dhruvildave/top-play-store-games


## Lancer les scripts
Nous n'avons pas de WebApp. 
Vous pouvez retrouvez notre notebook dans notre git.

### Base de données sur Atlas
Nous avons déployé la base de donnée sur Atlas. Vous avez dû recevoir une invitation sur votre email : **sayf.bejaoui@ynov.com**
![image](https://user-images.githubusercontent.com/57988637/169692903-008fb731-a20c-4672-972f-5e00ea021491.png)
https://cloud.mongodb.com/v2/628246003b6d4c5733157d5f#metrics/replicaSet/628247092d887604f812b66c/explorer/AndroidGames/games/find

### Notebook 
Vous pourrez exécuter le notebook à l'aide de jupyter en vous plaçant dans le bon dossier : 
- Installer jupyter : 
 ```sh
pip install jupyter
```

- Le lancer : 
 ```sh
jupyter-notebook NoSQL.ipynb
```

Vous y retrouverez : 
- La connexion à la base de donnée
- Les problèmes rencontrées sur le jeu de données
- Comment nous avons exploré et nettoyé les données
- un CRUD
- La réponse à nos 5 questions : 
  - les jeux avec la meilleur progression de vente les 30 derniers jours
  - Quel genre de jeux plais le moins ?
  - Quelle est la note des jeux qui se téléchargent le plus
  - Quel jeux ont plus de 50.00M de téléchargement ?
  - Top 5 des jeux gratuits les plus jouées


Si jamais vous voulez tester de votre côté la base de données voici les identifiants : 
 ```
 Username : NoSQLG9
Password : XnLzzU4vOLeEwiA5
 ```


## Trello 
Nous nous sommes réparti les tâches à l'aide de Trello, voici le lien :
https://trello.com/b/XwuvJGKq/nosql

## Présentation 
Voici le lien de notre présentation : 
https://docs.google.com/presentation/d/1f7Br0J6iFjwMNx5wGqK-TqYFDc_PaLYD9dRC8_VNsIg/edit?usp=sharing
(Si nous n'arrivez pas à y accéder il est également dans le git)

## Difficultés rencontrées 
Les deux principales difficultés :

### Atlas
Nous n'avions jamais utilisé Atlas, ni tout simplement mettre en production une base de données auparavant.
Nous n'avons pas eu de mal a créer la base de données, la remplir avec notre dataset.
Cependant nous n'arrivions pas à nous connecter à la base de données distantes pour faire nos requêtes.
Sur les 3 membres de l'équipe, 2 étaient à l'école en présentiel.
Les deux présents ont réussi, cependant l'autre avait des erreurs. Nous ne comprenions pas pourquoi.
En rentrant chez nous, nous avions nous aussi l'erreur.
Nous avons compris après qu'il fallait ajouter nos IPs sur Atlas pour autoriser la connexion.


### Deepnote
Nous voulions utiliser Deepnote pour faire un notebook
Nous avions l'habitude de travailler avec cette outil qui permet la collaboration en temps réel de notre notebook, qui s'éxcute dans le Cloud.
Il existe une version gratuite, et une payante.
Malheureusement, pour se connecter avec une base de données, il nous fallait la version payante. 
Nous avons perdu du temps là dessus car nous ne comprennions pas pourquoi cela ne marche pas.
Après de nombreuses recherches, essaies et tutos , nous avons compris que nous n'avions pas la bonne version.
Nous nous sommes donc tourné vers un Git où se trouve notre notebbok que nous utilisons via Jupyter pour ne pas avoir ce soucis de connexion de base de données
