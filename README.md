Voici un TOS sur le démarrage de Blue Print dans Azure ! 

# Création d'un Blue Print

Dans la ressource Azure Blue print : 

![Texte alternatif](image/1.png)

Création d'un blue print vide. 

Ajout d'un nom, d'une description, de l'abonnement Azure : 

![Texte alternatif](image/2.png)

Puis nous pouvons sélectionner un artefact comme par exemple, l'ajout d'un groupe de ressources : 

![Texte alternatif](image/3.png)

Puis nous ajoutons un deuxiéme artefact de type ARM afin de déployer un VNET (Fichier ARM dispo dans le GIT) : 

![Texte alternatif](image/4.png)

Il est important de spécifier les parametres : 

![Texte alternatif](image/5.png)

Nous pouvons enregistrer le brouillon. 

![Texte alternatif](image/6.png)

Nous publions le Blue Print : 

![Texte alternatif](image/7.png)

Ajout d'un numéro de version : 

![Texte alternatif](image/8.png)

Affectation du Blue Print : 

![Texte alternatif](image/9.png)

Nous devons remplir le nom de l'affectation : 

![Texte alternatif](image/10.png)

Le Blue Print est en cours de déploiement : 

![Texte alternatif](image/11.png)

Ensuite dans la section Azure "Groupe de ressources", vous devez trouver votre groupe de ressources avec le VNET disponible. En cas de non déploiement, une erreur sera affiché avec la problématique rencontrée. 