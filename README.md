![Naas.ai - Open Source Data Platform](assets/project_logo.png)




# **FEC engine - La solution pour exploiter la data de ta compta! 💰🇫🇷**

# **Installation**

Avant d'utiliser FECthis, assurez-vous de suivre les étapes faciles ci-dessous :

## **Étape 1 : Créer un compte Naas.ai (Naas Lab uniquement disponible pour les comptes professionels)**

https://www.naas.ai/

## **Étape 2 : Clone ce dossier sur ton compte Naas.ai**

https://github.com/jupyter-naas/FEC-engine.git

## **Étape 3 : Lance le fichier setup.ipynb**

L'exécution de ce fichier va permettre d'installer les librairies nécessaires au projet.

## **Étape 4 : Accède au Dashboard**

1. Lancez le fichier run_dashboard.ipynb présent à la racine du projet
2. Accèdez au dasboard via l'URL: https://app.naas.ai/user/{user_account}/proxy/8050/

## **Étape 5 : Personaliser son moteur**

Vous pouvez maintenant ajouter 2 fichiers FEC de votre entreprise pour 2 années conséquitives en cliquant sur la roue crantée en haut à droite.

1. Choisissez vos FECs sur votre PC
2. Lorsque le format a bien été validé, vous pouvez cliquer sur "Executé le pipeline" pour mettre à jour les données.
3. Une fois terminé, veuillez raffraichir votre page pour accéder aux nouvelles données.

# **Benefices**

Avec FECthis, vous pouvez facilement :

- Visualiser les données financières de votre entreprise avec un tableau de bord Dashboard Ploty convivial et adaptable à tout support (PC et mobile).
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
- Le dossier **`/tests`**/tests stocke tous les tests à effectuer avant la production.
- Le dossier **`/utils`** stocke toutes les fonctions communes utilisées dans les fichiers.
- Le fichier **`requirements.txt`** répertorie tous les packages et dépendances.
- Le fichier **`setup.ipynb`** exécute le produit sur un serveur Naas.



# **Combien ça coute?**



# **Contactez-nous**

Si vous souhaitez personnaliser le tableau de bord FECthis ou développer une solution similaire pour votre entreprise en utilisant d'autres sources de données, contactez-nous!

Email: fecthis@naas.ai <br>
 


# **Ressources**
- Guide d'installation vidéo 
- [Slides de présentation](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5144ca51-081)
