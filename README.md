![Naas.ai - Open Source Data Platform](assets/project_logo.png)




# **FECthis - La solution pour exploiter la data de ta compta en seulement 5 min top chrono! 💰🇫🇷**

[![Installation video guide](https://img.youtube.com/vi/UAhkbwXmjh4/maxresdefault.jpg)](https://www.youtube.com/watch?v=UAhkbwXmjh4)

FECthis est un moteur de données (data engine, en anglais) créée par l'équipe de Naas et Alexandre Stevens qui permet d'exploiter facilement les données comptables de votre entreprise à partir du fichier d'écritures comptables fourni par votre expert-comptable préféré.

Ce moteur de données est le fruit de la fusion de deux technologies puissantes, NAAS.AI et POWER BI, et il se compose de deux parties principales : 
- un "backend" géré par naas.ai pour manipuler le fichier FEC
- un "frontend" tableau de bord Power BI pour visualiser vos données financières.

# **Installation**

Avant d'utiliser FECthis, assurez-vous de suivre les étapes faciles ci-dessous :

## **Prérequis**
Système d'exploitation : Windows<br>
Niveau : Facile<br>
Durée d'installation : 5 minutes<br>
Support d'installation : Guide vidéo et guide écrit<br>


## **Étape 1 : Créer un compte gratuit Naas.ai**

https://www.naas.ai/free-forever

## **Étape 2 : Clone ce dossier sur ton compte Naas.ai**

https://www.naas.ai/free-forever

## **Étape 3 : Lance le fichier settings.ipynb**

1. Créer un dossier spécifique (exemple : "TEST_FECTHIS")
2. Lancer le script /models/v0/script les deux fichiers FEC
3. Ajouter éventuellement le logo de votre entreprise
4. Lancer le script "models/v0/script.ipynb"
5. Copier le dernier URL généré dans naas.ai pour le coller dans Power BI

## **Étape 4 : Ouvrir le tableau de bord Power BI**


1. Modifier les paramètres et coller l'URL copié précédemment
2. Actualiser le tableau de bord
3. Une popup apparaîtra pour l'authentification, sélectionner "Anonyme" et cliquer sur "Se connecter"
4. Profitez de votre nouveau tableau de bord financier !

## **Étape 5 : Personaliser son moteur**

Vous pouvez maintenant ajouter 2 fichiers FEC de votre entreprise pour 2 années conséquitives. 

Vous pouvez aussi ajouter votre logo d'entreprise, il suffit de suivre les étapes suivantes :

- Aller dans le dossier /assets et ajouter un fichier image du logo de votre entreprise.
- Ouvrir le fichier /models/v0/script.ipynb et localiser la cellule de code contenant la variable LOGO.
- Modifier la valeur de cette variable avec le nom de fichier et le chemin d'accès à votre fichier image logo. Par exemple, si vous avez ajouté un fichier appelé monlogo.png dans le dossier /assets, vous devriez modifier la variable comme suit : LOGO = "/assets/monlogo.png"


# **Benefices**

Avec FECthis, vous pouvez facilement :

- Visualiser les données financières de votre entreprise avec un tableau de bord Power BI convivial.
- Gagner du temps en évitant la saisie manuelle des données ou le besoin d'embaucher un comptable.
- Suivre votre performance financière en temps réel et prendre de meilleures décisions financières pour votre entreprise.
- Partager des informations et des rapports financiers avec votre équipe ou vos parties prenantes.

# **Comment ça marche?**


Naas.ai est un service cloud qui fournit une plateforme de gestion des données tout-en-un pour développer des solutions automatisée et facile à distribuer. Un Notebook est un document interactif qui permet aux utilisateurs de documenter, créer et d'exécuter du code, de visualiser des données, de créer des visualisations. Naas fournit une infrastructure pour exécuter ces Notebooks en production, de manière sécurisée et dans le cloud.

Le Data Product Framework est une approche pour développer des produits de données qui impliquent plusieurs étapes telles que la collecte de données, le nettoyage, la transformation, la modélisation et l'analyse. Il est conçu pour aider les équipes à collaborer efficacement sur les projets de données, en leur fournissant un cadre de travail structuré.

Le Data Product Framework est structuré, avec des dossiers organisés tels que /assets, /inputs, /models, /outputs, /tests et /utils.

En utilisant Naas et le Data Product Framework, les équipes peuvent collaborer efficacement sur des projets de données, en travaillant sur des mêmes documents distribués dans le cloud. 
Les fichiers et dossiers organisés permettent de gérer efficacement les données et les modèles, tandis que les outils tels que requirements.txt et settings.ipynb facilitent l'exécution et la mise à jour du produit.

## Définitions

- Le dossier **`/assets`**  stocke tout fichier PNG, JPG, GIF, CSV, diagrammes ou diapositives liés à la documentation du produit.
- Le dossier **`/inputs`** stocke les paramètres et tous les autres fichiers nécessaires (données, référentiel) pour exécuter les fichiers du dossier /models.
- Le dossier **`/models`** stocke tous les scripts qui transforment les entrées en sorties (notebook, fichiers Python, SQL). 
    *La collection de modèles open source de Naas peuvent être utilisés comme point de départ pour créer de nouvelles customisations du produit*
- Le dossier **`/outputs`** stocke tous les fichiers qui seraient exposés en dehors du serveur Naas.
- Le dossier **`/outputs`**/tests stocke tous les tests à effectuer avant la production.
- Le dossier **`/utils`** stocke toutes les fonctions communes utilisées dans les fichiers.
- Le fichier **`requirements.txt`** répertorie tous les packages et dépendances.
- Le fichier **`settings.ipynb`** exécute le produit sur un serveur Naas.
- Le fichier **`update.ipynb`** extrait à nouveau ce référentiel.



# **Combien ça coute?**



# **Contactez-nous**

Si vous souhaitez personnaliser le tableau de bord FECthis ou développer une solution similaire pour votre entreprise en utilisant d'autres sources de données, contactez-nous!

Email: fecthis@naas.ai <br>
 


# **Ressources**
- Guide d'installation vidéo 
- [Slides de présentation](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5144ca51-081)