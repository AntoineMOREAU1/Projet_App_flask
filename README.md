# Projet_App_flask

Ce projet consiste en la création d'une application flask, qui utlise des outils tel que MongoDB, scrapy, et docker compose 

# Descsription 

Aujourd’hui, de nombreux sites existent pour répertorier le données météorologique des différents spots de surf. Or étant moi même surfeur je me suis rendu compte que cela prenait beaucoup de temps d’analyser les nombreuses données pour chaque spots et chaque jours lorsque je recherche un endroit pour aller surfer.
Le but de cette application est de récolter les données des différents spots de surf en France sur le site "https://www.surf-report.com/" à l’aide scrappy, une fois c’est données stockées l’affichage se fait via une application web en utilisant le framework Flask. Mongodb a été utilisé pour créer la base de données et permettre les requêtes.
Afin d’analyser via des graphiques les conditions météorologiques moyennes des différents spots Dash a été utilisé .
Enfin Docker a permis la virtualisation d’un serveur pour la base de donnée mongo.


# Lancement du programme 

1) Lancer dans un premier temps docker :

docker-compose up 


2) Executer le script pyhton :

App_web.py

3) Se rendre à l'adresse indiquée par le terminal 


# Résultat 

# Page d'aceuil
![Page_acceuil](https://github.com/AntoineMOREAU1/Projet_App_flask/blob/master/img_read_me/Page_acceuil.png)

# Selection du spot par critéres
![Choix_des_critéres.png](https://github.com/AntoineMOREAU1/Projet_App_flask/blob/master/img_read_me/Choix_des_critéres.png)

# Affichage des spots correspondant aux critéres 
![Affichage_des_spots](https://github.com/AntoineMOREAU1/Projet_App_flask/blob/master/img_read_me/Affichage_des_spots.png)

# Accés à des dashboards pour mieux comprendre les conditions sur l'ensemble du terrritoire 
![Menu_déroulant](https://github.com/AntoineMOREAU1/Projet_App_flask/blob/master/img_read_me/Menu_déroulant.png)


![DashBoard](https://github.com/AntoineMOREAU1/Projet_App_flask/blob/master/img_read_me/Dashboard.png)
